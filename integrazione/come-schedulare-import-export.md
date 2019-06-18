# Come schedulare Import/Export

Kimo espone le procedure di Import/Export sottoforma di webapi.  
L'url di invocazione è nella forma:  
https://kimo.mycompany.com/server/Integration/&lt;endpoint&gt;  
  
Dove l'endpoint può assumere uno dei seguenti:

| Endpoint | Descrizione |
| :--- | :--- |
| FullImportFromErp | Esegue l'Import completa dei dati da Erp |
| ImportFromErp | Esegue l'Importi parziale dei dati da Erp per le sole Entità specificate in query string Es. ImportFromErp?tables=Item,ItemOfflineAvailability |
| LoadFromIntegrator |  |
| ImportFiles |  |
| DownloadItemsImages |  |
| GeocodeAddresses |  |
| SyncDataCreation |  |
| SettingsSyncDataCreation |  |
| LoadFromIntegratorAndPrepareSyncData |  |
| ExportToErp | Esegue l'Export completa verso l'Erp |

Le webapi supportano in verbo http GET.  
L'esecuzione della webapi è asincrona pertanto alla ricezione della GET viene inviata una generica risposta.  
Il servizio scarta la richiesta se un precedente comando è ancora in esecuzione.  
Se la richiesta viene accettata, al termine dell'esecuzione  viene inviata un'email di notifica al destinatari impostati.   
E' possibile specificare specifiche liste di destinatari in base all'esito dell'esecuzione \(vedi [Impostazioni di sistema](../impostazioni/impostazioni-di-sistema.md) NotificationCenter\ErrorRecipients e NotificationCenter\InfoRecipients\).

Lo stato avanzamento dell'esecuzione può essere monitorato utilizzando il tool Smart Mobile Mongo Log Viewer.  
  
L'invocazione del servizio può essere effettuata usando il tool che si preferisce Es. Postman, Web Browser o script VB.  
  
A seguire un esempio di script VB che invoca il servizio di FullImportFromErp:

```csharp
Call LogEntry()

Sub LogEntry()
  'Force the script to finish on an error.
  On Error Resume Next

  'Declare variables
  Dim objRequest
  Dim URL

  Set objRequest = CreateObject("Microsoft.XMLHTTP")

   'Put together the URL link appending the Variables.
   URL = "https://admin:SysAdmin@kimo.mycompany.com/server/Integration/FullImportFromErp"

   'Open the HTTP request and pass the URL to the objRequest object
   objRequest.open "GET", URL , false

   'Send the HTML Request
   objRequest.Send

   'Set the object to nothing
   Set objRequest = Nothing
End Sub
```

L'utilizzo di uno script rende possibile l'invocazione schedulata del servizio.  
Per esempio nel caso di Windows si può utilizzare il tool "Task Scheduler". 

