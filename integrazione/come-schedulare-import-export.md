# Come schedulare Import/Export

Kimo espone le procedure di Import/Export sottoforma di webapi.\
L'url di invocazione è nella forma:\
https://kimo.mycompany.com/server/Integration/\<endpoint>\
\
Dove l'endpoint può assumere uno dei seguenti valori:

| Endpoint                             | Descrizione                                                                                                                                    |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| FullImportFromErp                    | Esegue l'Import completa dei dati da Erp                                                                                                       |
| ImportFromErp                        | Esegue l'Importi parziale dei dati da Erp per le sole Entità specificate in query string Es. ImportFromErp?tables=Item,ItemOfflineAvailability |
| LoadFromIntegrator                   | Esegue il caricamento dati da database Sql (KimoIntegrator) a MongoDb                                                                          |
| ImportFiles                          | I file specificati nelle impostazioni vengono importati nel server di Kimo e resi disponibili per la sincronizzazione                          |
| DownloadItemsImages                  | Esegue il download delle immagini degli articoli presenti nella ItemURL                                                                        |
| GeocodeAddresses                     | Esegue la geocodifica di tutti gli Account                                                                                                     |
| SyncDataCreation                     | Esegue la preparazione dei dati per gli utenti di tipo Agente                                                                                  |
| SettingsSyncDataCreation             | Esegue la preparazione dei dati, delle sole impostazioni,  per gli utenti di tipo Agente                                                       |
| LoadFromIntegratorAndPrepareSyncData | Esegue sequenzialmente LoadFromIntegrator e SyncDataCreation                                                                                   |
| ExportToErp                          | Esegue l'Export completa verso l'Erp                                                                                                           |

Le webapi supportano il verbo http GET.\
L'esecuzione della web api è asincrona pertanto alla ricezione della GET viene inviata una generica risposta.\
Il servizio scarta la richiesta se un precedente comando è ancora in esecuzione.\
Se la richiesta viene accettata, al termine dell'esecuzione  viene inviata un'email di notifica al destinatari impostati. \
E' possibile specificare specifiche liste di destinatari in base all'esito dell'esecuzione (vedi [Impostazioni di sistema](../impostazioni/impostazioni-di-sistema.md) NotificationCenter\ErrorRecipients e NotificationCenter\InfoRecipients).

L'utilizzo di uno script rende possibile l'invocazione schedulata del servizio.\
Per esempio nel caso di Windows si può utilizzare il tool "Task Scheduler".&#x20;
.