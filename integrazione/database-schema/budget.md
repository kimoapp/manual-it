# Budget
Budget

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| Amount | Importo | dec |  |
| AverageUnitPrice | Prezzo unitario medio | dec |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Description | Note | text | text |
| [EntityStatus](#entitystatus) | Campo che definisce lo stato del record | enum |  |
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
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| Quantity | Quantità | dec |  |
| SalesAgentId |  | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| SyncReference | Riferimento | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| UomId | Unità di misura | text | 10 |
| UploadToServerTimeStamp |  | dt |  |

EntityStatus
---
0: ImportedFromErp<br>1: ExportedToErp<br>2: ImportedByErp<br>3: ExportingToErp<br>4: Deleted<br>5: CommittingExportToErp<br>6: ToExportToErp<br>7: Editing<br>8: UploadedToServer<br>10: EditingPending

