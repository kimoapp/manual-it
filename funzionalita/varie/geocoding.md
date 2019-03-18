# Geocoding

Nell'applicazione Kimo B2A per iPad è possibile visualizzare su una mappa interattiva gli indirizzi dei clienti.   
Questa funzionalità richiede l'utilizzo delle [Geocoding API](https://developers.google.com/maps/documentation/geolocation/intro) di Google.  
Per poterla attivare è necessario creare una API Key tramite la [Google Cloud Platform Console](https://console.cloud.google.com/google/maps-apis).   
Questa operazione è possibile effettuarla seguendo le istruzioni presenti nel seguente link:  
[https://developers.google.com/maps/documentation/geocoding/get-api-key](https://developers.google.com/maps/documentation/geocoding/get-api-key)  
Una volta ottenuta la chiave bisognerà impostarla nella console di amministrazione di Kimo effettuando i seguenti passaggi:

1. Effettuare il login nella console di amministrazione;
2. Aprire la sezione **Impostazioni** tramite la voce presente nel menu laterale di sinistra e selezionare la voce **Business rules;**
3. Verificare se è presente nella lista delle regole di business la Chiave "**Api\GoogleMapKeys**";
4. Se non è presente creare una nuova regola di business tramite il bottone "**Nuova"**, inserendo come Chiave "**Api\GoogleMapKeys**" e come Valore la chiave precedentemente creata sulla Google Cloud Platform Console.



