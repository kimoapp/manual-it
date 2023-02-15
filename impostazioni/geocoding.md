# Impostazione chiave Google \(Geocoding\)

Kimo utilizza le [Geocoding API](https://developers.google.com/maps/documentation/geolocation/intro) di Google.  
Per poterle usare è necessario creare una API Key tramite la [Google Cloud Platform Console](https://console.cloud.google.com/google/maps-apis), ed impostarla nella console di amministrazione di Kimo.   
È possibile generare una API Key seguendo le istruzioni presenti al seguente link:  
[https://developers.google.com/maps/documentation/geocoding/get-api-key](https://developers.google.com/maps/documentation/geocoding/get-api-key)  
Una volta ottenuta la chiave sarà possibile impostarla nella console di amministrazione di Kimo effettuando i seguenti passaggi:

1. Effettuare il login nella console di amministrazione;
2. Aprire la sezione **Impostazioni** tramite la voce presente nel menu laterale di sinistra e selezionare la voce **Business rules;**
3. Verificare se è presente nella lista delle regole di business la Chiave "**Api\GoogleMapKeys**";
4. Se non è presente creare una nuova regola di business tramite il bottone "**Nuova"**, inserendo come Chiave "**Api\GoogleMapKeys**" e come Valore la chiave precedentemente creata sulla Google Cloud Platform Console.





.