# Catalogo PDF (SFA)

Kimo supporta delle operazioni "interattive" sui cataloghi esportati come file PDF. In particolare è possibile:

1. Inserire gli articoli nei documenti di vendita cliccando sul PDF.
2. Ricercare articoli specifici nel catalogo di Kimo cliccando su un'area del PDF.&#x20;

Il PDF conterrà dei link in concomitanza di specifiche aree: il formato di questi link farà sì che si scatenerà l'operazione richiesta, come l'inserimento dell'articolo nel documento.

Se sono presenti più file PDF, l'agente selezionerà quello di suo interesse.

## Configurazione generale

1. Nei "Server System Settings" configurare il percorso della directory da cui importare i file PDF tramite l'impostazione "PdfCatalog\SourceDirectory".\


### Configurazione per l'inserimento di articoli nei documenti di vendita

Abilitare il ruolo che permette l'inserimento di articoli dal catalogo PDF nei documenti di vendita.

I file PDF devono contenere dei link che permettano l'inserimento degli articoli nei documenti.\
Tali link devono essere nel formato

```http
kimo://add-item
```

Esempi:

```http
kimo://add-item?item=01405
kimo://add-item?item=01405&salesQty=10&freeGiftSalesQty=2&priceList=Listino1
kimo://add-item?manufacturerId=BTI&manufacturerItemId=5001
kimo://add-item?manufacturerId=BTI&manufacturerItemId=5001&salesQty=10
kimo://add-item?externalManufacturerId=BTC&manufacturerItemId=5001&salesQty=10
```

Parametri supportati:

| Parametro              | Descrizione                                                                                               | Parametri riconosciuti                                                                                                      | Tipo    |
| ---------------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------- |
| item                   | Articolo (codice)                                                                                         | itemId, item, cod                                                                                                           | string  |
| manufacturerId         | Codice produttore in Kimo                                                                                 | manufacturer, manufacturerid, manufacturerId, ManufacturerId                                                                | string  |
| externalManufacturerId | Codice produttore esterno a Kimo (Es. Codice produttore presente su ilDataPool)                           | <p>externalmanufacturerId,<br>externalManufacturerId,</p><p>ExternalManufacturerId</p>                                      | string  |
| manufacturerItemId     | Codice articolo produttore                                                                                | <p>manufactureritemid,</p><p>manufacturerItemId</p><p>ManufacturerItemId,</p><p>CodiceArticoloProduttore,</p><p>artProd</p> | string  |
| salesQty               | Quantità di vendita                                                                                       | salesQty                                                                                                                    | decimal |
| freeGiftSalesQty       | <p>Quantità di vendita in omaggio<br>(usabile solo valorizzando anche il parametro 'salesQty')</p><p></p> | freeGiftSalesQty                                                                                                            | decimal |
| priceList              | Listino prezzi (codice)                                                                                   | priceList                                                                                                                   | string  |

{% hint style="warning" %}
Se i codici (articolo, produttore, articolo-produttore) contengono caratteri "particolari" (es. spazi, punti, ...) vanno codificati secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref\_urlencode.asp)\
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
{% endhint %}

{% hint style="warning" %}
Per essere valido il link deve contenere almeno 1 di queste tre informazioni essenziali:

* item
* manufacturerId + manufacturerItemId
* externalManufacturerId + manufacturerItemId
{% endhint %}

### Configurazione per ricercare articoli specifici nel catalogo di Kimo

Abilitare il ruolo che permette l'inserimento di articoli dal catalogo PDF nei documenti di vendita.

I file PDF devono contenere dei link che, una volta cliccati dall'utente, avviino la ricerca degli articoli nel catalogo di Kimo. Tali link devono essere nel formato

```http
kimo://search-items
```

Esempi:

```http
kimo://search-items?item=01405
kimo://search-items?item=01405&item=01406&item=13342
```

Parametri supportati:

| Parametro | Descrizione                                                                   | Tipo   | Obbligatorio |
| --------- | ----------------------------------------------------------------------------- | ------ | ------------ |
| item      | <p>Elenco degli articoli <br>(il parametro può essere ripetuto più volte)</p> | string | Sì           |

{% hint style="warning" %}
Se il codice articolo contiene caratteri "particolari" (es. spazi, punti, ...) va codificato secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref\_urlencode.asp)\
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
{% endhint %}
.