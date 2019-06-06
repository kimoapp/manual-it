# Catalogo da PDF

Kimo supporta delle operazioni "interattive" sui cataloghi esportati come file PDF. In particolare è possibile:

1. Inserire gli articoli nei documenti di vendita cliccando sul PDF.
2. Ricercare articoli specifici nel catalogo di Kimo cliccando su un'area del PDF.  

![](https://kimostorage.blob.core.windows.net/kimomanual/Images/PDF%20Catalog.gif)

Il PDF conterrà dei link in concomitanza di specifiche aree: il formato di questi link farà sì che si scatenerà l'operazione richiesta, come l'inserimento dell'articolo nel documento.

Se sono presenti più file PDF, l'agente selezionerà quello di suo interesse.

## Configurazione generale

1. Nei "Server System Settings" configurare il percorso della directory da cui importare i file PDF tramite l'impostazione "PdfCatalog\SourceDirectory". 

### Configurazione per l'inserimento di articoli nei documenti di vendita

Abilitare il ruolo che permette l'inserimento di articoli dal catalogo PDF nei documenti di vendita.

I file PDF devono contenere dei link che permettano l'inserimento degli articoli nei documenti.  
Tali link devono essere nel formato

```http
kimo://add-item
```

Esempi:

```http
kimo://add-item?item=01405
kimo://add-item?item=01405&salesQty=10&freeGiftSalesQty=2&priceList=Listino1
```

Parametri supportati:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parametro</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Tipo</th>
      <th style="text-align:left">Obbligatorio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">item</td>
      <td style="text-align:left">Articolo (codice)</td>
      <td style="text-align:left">string</td>
      <td style="text-align:left">S&#xEC;</td>
    </tr>
    <tr>
      <td style="text-align:left">salesQty</td>
      <td style="text-align:left">Quantit&#xE0; di vendita</td>
      <td style="text-align:left">decimal</td>
      <td style="text-align:left">No</td>
    </tr>
    <tr>
      <td style="text-align:left">freeGiftSalesQty</td>
      <td style="text-align:left">
        <p>Quantit&#xE0; di vendita in omaggio
          <br />(usabile solo valorizzando anche il parametro &apos;salesQty&apos;)</p>
        <p></p>
      </td>
      <td style="text-align:left">decimal</td>
      <td style="text-align:left">No</td>
    </tr>
    <tr>
      <td style="text-align:left">priceList</td>
      <td style="text-align:left">Listino prezzi (codice)</td>
      <td style="text-align:left">string</td>
      <td style="text-align:left">No</td>
    </tr>
  </tbody>
</table>{% hint style="warning" %}
Se il codice articolo contiene caratteri "particolari" \(es. spazi, punti, ...\) va codificato secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref_urlencode.asp)  
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
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

| Parametro | Descrizione | Tipo | Obbligatorio |
| :--- | :--- | :--- | :--- |
| item | Elenco degli articoli  \(il parametro può essere ripetuto più volte\) | string | Sì |

{% hint style="warning" %}
Se il codice articolo contiene caratteri "particolari" \(es. spazi, punti, ...\) va codificato secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref_urlencode.asp)  
Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A".
{% endhint %}

