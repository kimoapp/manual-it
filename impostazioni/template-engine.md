# Motore di template \(Template Engine\)

Kimo utilizza un motore di template \(Template Engine\) per comporre alcune stringhe personalizzabili. Ad esempio, tale motore viene utilizzato per renderizzare i layout basati sull'HTML \(come quelli per la scheda cliente e scheda articolo\) o alcune Regole di Business, come  "Document\QuantitiesSummaryTemplate".

## Sintassi per i parametri

Data una variabile di tipo semplice chiamata "Item", è possibile renderizzarla inserendo nel testo del template uno dei seguenti valori:

1. $Item
2. ${Item}

{% hint style="danger" %}
Se la variabile ha valore NULL, utilizzare l'operatore '!' descritto di seguito per evitare che venga renderizzata con il nome stesso della variabile invece che come stringa vuota.
{% endhint %}

Data una variabile di tipo oggetto, contente delle proprietà, è possibile renderizzarla utilizzando il '.' per indicare le proprietà. Ad esempio per referenziare la proprietà "Description" della variabile "Item" si potranno utilizzare le sintassi

1. $Item.Description
2. ${Item.Description}

{% hint style="danger" %}
Se la variabile ha valore NULL, utilizzare l'operatore '!' descritto di seguito per evitare che venga renderizzata con il nome stesso della variabile invece che come stringa vuota.
{% endhint %}

## Operatore '!'

Quando una variabile ha valore NULL, di default non viene mostrata come una stringa vuota, ma viene mostrato il nome stesso della variabile: ad esempio, se la variabile nel template è indicata come "Item.Description", ma ha valore null, la stringa verrà renderizzata proprio come "$Item.Description" invece di stringa vuota.

Per evitare questo comportamento, va utilizzato l'operatore '!' \(chiamato 'Quiet Reference Notation' in letteratura\).  
Quindi la variabile andrà indicata nel template in uno dei seguenti modi:

1. $!Item.Description
2. $!{Item.Description}

## If / Else / End

Esempio:

```text
#if ($foo)
  TESTO QUANDO VERO
#else
  TESTO QUANDO FALSO
#end
```

Esempio in un'unica linea:

```text
#if ($foo) TESTO QUANDO VERO #else TESTO QUANDO FALSO #end
```

## Verifica parametri con valore Null

Il modo più semplice per verificare se un parametro ha valore null è di utilizzare la funzione "utils.IsNullOrEmpty" descritta nella sezione delle [funzionalità](../funzionalita/).

Esempio di utilizzo:

```text
#if (${utils.IsNullOrEmpty($ShipmentSite)}) 
  Stampa se null o stringa vuota 
#else 
  Stampa se valorizzato
#end
```

## Cicli foreach

Esempio:

```text
#foreach ($product in $allProducts)
    <li>$product</li>
#end
```

È possibile evitare di andare a capo dopo ogni iterazione usando i caratteri '\#\#':

```text
#foreach ($customer in $customerList)
$customer.Name##
#end
```

Sono supportate ulteriori istruzioni, per inserire dei valori tra gli elementi:

```text
#foreach($i in $items)
#each (this is optional since its the default section)
       text which appears for each item
#before
       text which appears before each item
#after
       text which appears after each item
#between
       text which appears between each two items
#odd
       text which appears for every other item, including the first
#even
       text which appears for every other item, starting with the second
#nodata
       Content rendered if $items evaluated to null or empty
#beforeall
       text which appears before the loop, only if there are items
       matching condition
#afterall
       text which appears after the loop, only of there are items
       matching condition
#end
```

## Dichiarazione di variabili

Esempio:

```text
#set ($index = 0)
#set ($index = $index + 1)
```

## Commenti

I commenti possono essere definiti usando i caratteri '\#\#':

`This text is visible. ## This text is not.`

## Funzioni per la formattazione

| Funzione | Parametri | Scopo |
| :--- | :--- | :--- |
| formatter.ToQuantity | decimal value | Formattazione come quantità \(fino a 5 decimali\) |
| formatter.ToUnitPrice | decimal value | Formattazione come prezzo unitario \(es. con 2 zeri dopo la virgola e fino a 5 decimali\) |
| formatter.ToTotalPrice | decimal value | Formattazione come importo totale \(es. con 2 zeri dopo la virgola e fino a 2 decimali\) |
| formatter.NumberToInvariantString | decimal value | Converte un numero in una stringa nel formato "invariant" \(usando il '.' per i decimali a prescindere dalla lingua e senza alcun separatore per le migliaia\) |
| formatter.ToMonthName | int month | Dato il numero di un mese, ne restituisce il nome |
| '${Number:00000}' |  | Esegue il padding della variabile 'Number', inserendo il corrispondente numero di '0' \(5 nell'esempio\). |

## Funzioni di utilità

| Funzione | Parametri | Scopo |
| :--- | :--- | :--- |
| utils.IsNullOrEmpty | oggetto | Restituisce un boolean che indica se l'oggetto passato come parametro è Null o se è una stringa vuota \(o contenente soli spazi\) |
| utils.Take | object lista, int count | Data una lista di valori, prende i primi n espressi dal parametro "count" |
| $newline o ${newline} |  | Interruzione di riga |
| Now |  | Restuisce la data in cui è stato renderizzato il template, nel formato "d MMM yyy HH.mm" \(es. "12 gen 2021 15.46"\)  |

## Chiamate a funzioni

È possibile invocare delle funzioni di sistema \(funzioni esposte dal .NET Framework\) tramite sintassi come:

```text
Testing ${val.ToString().Trim()}
Testing $val.ToString().Trim()
```

Analogamente è possibile invocare delle funzioni esposte dagli oggetti

```text
Testing ${test.CustomMethod(${val})}
Testing $test.CustomMethod(${val})
Testing $test.CustomMethod($val)
```

.