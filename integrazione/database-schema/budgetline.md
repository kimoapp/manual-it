---
description: Riga di un budget
---
# BudgetLine

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| Amount | Importo | dec |  |
| BudgetId | Id del budget | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| [EntityStatus](#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeDateTime1 | Campo datetime libero | date |  |
| FreeDateTime2 | Campo datetime libero | date |  |
| FreeDateTime3 | Campo datetime libero | date |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeDecimal4 | Campo decimale libero | dec |  |
| FreeDecimal5 | Campo decimale libero | dec |  |
| FreeDecimal6 | Campo decimale libero | dec |  |
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
| Locked | Bloccato | bool |  |
| LockedFields | Campi bloccati, non modificabili | text | text |
| Quantity | Quantità | dec |  |
| RevisedAmount | Importo revisionato | dec |  |
| RevisedQuantity | Quantità revisionata | dec |  |
| SyncReference | Riferimento | text | 50 |
| UomId | Unità di misura | text | 10 |
| UploadToServerTimeStamp |  | dt |  |

EntityStatus
---
0: ImportedFromErp&ltbr&gt;1: ExportedToErp&ltbr&gt;2: ImportedByErp&ltbr&gt;3: ExportingToErp&ltbr&gt;4: Deleted&ltbr&gt;5: CommittingExportToErp&ltbr&gt;6: ToExportToErp&ltbr&gt;7: Editing&ltbr&gt;8: UploadedToServer&ltbr&gt;10: EditingPending


