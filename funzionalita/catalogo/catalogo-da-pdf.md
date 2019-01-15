# Catalogo da PDF

Kimo supporta l'inserimento di articoli nei documenti di vendita a partire da uno o più file PDF. Gli agenti possono cliccare direttamente nel PDF per aggiungere gli articoli al documento.

![](https://kimostorage.blob.core.windows.net/kimomanual/Images/PDF%20Catalog.gif)

Il PDF conterrà dei link in concomitanza degli articoli: il formato di questi link farà sì che gli articoli saranno inseriti nei documenti.

{% embed url="https://kimostorage.blob.core.windows.net/kimomanual/Images/PDF%20Catalog.mp4" %}



Se sono presenti più file PDF, l'agente selezionerà quello di suo interesse in fase di inserimento articoli nel documento.

{% embed url="https://kimostorage.blob.core.windows.net/kimomanual/Images/PDF%20Catalog.webm" %}



## Configurazione

1. Nei "Server System Settings" configurare il percorso della directory da cui importare i file PDF tramite l'impostazione "PdfCatalog\SourceDirectory".
2. Abilitare il ruolo che permette l'inserimento di articoli dal catalogo PDF nei documenti di vendita.
3. I file PDF devono contenere dei link che permettano l'inserimento degli articoli nei documenti. Tali link devono essere nel formato kimo://add-item?itemId={codice articolo} Esempio: kimo://add-item?itemId=01405
   1. Se il codice articolo contiene caratteri "particolari" \(es. spazi, punti, ...\) va codificato secondo lo standard di codifica degi url [https://www.w3schools.com/tags/ref\_urlencode.asp](https://www.w3schools.com/tags/ref_urlencode.asp) Ad esempio il codice articolo "ARTICOLO A" diventa "ARTICOLO%20A". 

