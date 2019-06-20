# Motore di template \(Template Engine\)

Kimo utilizza un motore di template \(Template Engine\) per comporre alcune stringhe personalizzabili. Ad esempio, tale motore viene utilizzato per renderizzare i layout basati sull'HTML \(come quelli per la scheda cliente e scheda articolo\) o alcune Regole di Business, come  "Document\QuantitiesSummaryTemplate".

## Sintassi per i parametri

Data una variabile di tipo semplice chiamata "Item", è possibile renderizzarla inserendo nel testo del template uno dei seguenti valori:

1. $Item
2. ${Item}

Data una variabile di tipo oggetto, contente delle proprietà, è possibile renderizzarla utilizzando il '.' per indicare le proprietà. Ad esempio per referenziare la proprietà "Description" della variabile "Item" si potranno utilizzare le sintassi

1. $Item.Description
2. ${Item.Description}

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
| utils.Take | object lista, int count | Data una lista di valori, prende i primi n espressi dal parametro "count" |
| $newline o ${newline} |  | Interruzione di riga |

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

