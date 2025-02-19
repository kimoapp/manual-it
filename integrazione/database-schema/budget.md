---
description: Budget
---

# Budget

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Amount | Importo | dec |  |
| AverageUnitPrice | Prezzo unitario medio | dec |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Description | Note | text | text |
| [EntityStatus](budget.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeLookup1 | Id per dato tabellato | text | 50 |
| FreeLookup2 | Id per dato tabellato | text | 50 |
| FreeLookup3 | Id per dato tabellato | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| ItemCollectionId | Id della collezione articolo | text | 50 |
| ItemLineId | Id della line articolo | text | 50 |
| ItemSeriesId | Id della serie articolo | text | 50 |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| ManufacturerId | Id del produttore | text | 50 |
| Quantity | Quantità | dec |  |
| SalesAgentId |  | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| SyncReference | Riferimento | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| UomId | Unità di misura | text | 10 |
| UploadToServerTimeStamp |  | dt |  |

## EntityStatus

* 0: ImportedFromErp
* 1: ExportedToErp
* 2: ImportedByErp
* 3: ExportingToErp
* 4: Deleted
* 5: CommittingExportToErp
* 6: ToExportToErp
* 7: Editing
* 8: UploadedToServer
* 9: StartedUploadToServer
* 10: EditingPending
* -1: Undefined
