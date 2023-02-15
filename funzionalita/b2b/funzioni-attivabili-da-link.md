# Funzioni attivabili da link

Kimo B2B supporta la possibilità di richiamare alcune funzionalità attraverso link esterni, che potrebbero essere inseriti ad esempio in PDF, e-mail e così via.

Le funzionalità supportate sono:

1. [Apertura della scheda di un articolo](funzioni-attivabili-da-link.md#aggiunta-di-un-articolo-al-carrello-corrente)
2. [Aggiunta di un articolo al carrello corrente](funzioni-attivabili-da-link.md#aggiunta-di-un-articolo-al-carrello-corrente-1)

{% hint style="danger" %}
Nell'url di base va utilizzato il carattere '#', richiesto dal meccanismo di "routing" del B2B.\
Ad esempio, l'url utilizzato per l'apertura di una scheda articolo sarà:\
https://kimo.mycompany.com/#/items/000004
{% endhint %}

## Apertura della scheda di un articolo

Esempi:

```http
https://kimo.mycompany.com/#/items/000004
https://kimo.mycompany.com/#/items/articolo%20a
```

{% hint style="warning" %}
Se i codici (articolo, produttore, articolo-produttore) contengono caratteri "particolari" (es. spazi, punti, ...) vanno codificati secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref\_urlencode.asp)\
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
{% endhint %}

## Aggiunta di un articolo al carrello corrente

{% hint style="warning" %}
Questa funzionalità richiede che la quantità sia specificata nel link.\
Se si vuole dare la possibilità di aggiungere un articolo facendo sì che l'utente indichi la quantità, si può utilizzare il link che permette di aprire la scheda dell'articolo: all'interno della scheda, l'utente potrà specificare la quantità.
{% endhint %}

Esempi:

```http
https://kimo.mycompany.com/#/add-item?item=01405&salesQty=10
```

Parametri supportati:

| Parametro | Descrizione         | Parametri riconosciuti | Tipo    |
| --------- | ------------------- | ---------------------- | ------- |
| item      | Articolo (codice)   | itemId, item, cod      | string  |
| salesQty  | Quantità di vendita | salesQty               | decimal |

{% hint style="warning" %}
Se i codici (articolo, produttore, articolo-produttore) contengono caratteri "particolari" (es. spazi, punti, ...) vanno codificati secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref\_urlencode.asp)\
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
{% endhint %}

.