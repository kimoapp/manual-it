# Gestione avanzata dei preventivi

In Kimo, l'agente ha la possibilità di archiviare o posticipare in tempo reale i preventivi generati direttamente sul gestionale. Questa comunicazione avviene attraverso l'uso di tabelle. Per abilitare questa funzionalità, il gestionale deve rendere disponibile una tabella dotata dei seguenti campi:

| Campo                                                                  | Descrizione                                 | Tipo |
| ---------------------------------------------------------------------- | ------------------------------------------- | ---- |
| RequestId                                                              | id richiesta                                | text |
| RequestDate                                                            | data in cui è stata effettuata la richiesta | dt   |
| SalesAgentId                                                           | id agente                                   | text |
| ErpDocumentId                                                          | id documento da erp                         | text |
| ExpectedClosingDate                                                    |                                             | dt   |
| ArchivingReasonId                                                      | id causale di archiviazione                 | text |
| ArchivingNotes                                                         | nota di archiviazione                       | text |
| [OperationType](gestione-avanzata-dei-preventivi.md#operationtype)     | tipo di operazione                          | enum |
| [OperationResult](gestione-avanzata-dei-preventivi.md#operationresult) | esito operazione                            | enum |
| [Elaborated](gestione-avanzata-dei-preventivi.md#elaborated)           | stato elaborazione richiesta                | bool |

## OperationResult <a href="#operationresult" id="operationresult"></a>

* 0: WaitingForResult
* 1: Ok
* 2: GenericError
* 3: ErpTimedOut
* 4: ErpDocumentAlreadyArchivedOnErp
* 5: ErpDocumentAlreadyArchivedOnKimo

## OperationType

* 0: Undefined
* 1: Archiving
* 2: ExpectedClosingDateEdit

## Elaborated

* false: da elaborare
* true:  elaborato

