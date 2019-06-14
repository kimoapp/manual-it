---
description: Schede Marketing
---
# MarketingForm

<br>
**Chiavi**
- *Id*
- AccountId, FormTypeId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| [EntityStatus](#entitystatus) | Campo che definisce lo stato del record | enum |  |
| FormFamilyId | Id della famiglia della scheda marketing | text | 50 |
| FormTypeId | Id del tipo di scheda marketing | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| RegistryTypeId | Id del tipo di registrazione | text | 50 |
| SyncReference | Riferimento | text | 50 |
| UploadToServerTimeStamp |  | dt |  |

EntityStatus
---
0: ImportedFromErp&ltbr&gt;1: ExportedToErp&ltbr&gt;2: ImportedByErp&ltbr&gt;3: ExportingToErp&ltbr&gt;4: Deleted&ltbr&gt;5: CommittingExportToErp&ltbr&gt;6: ToExportToErp&ltbr&gt;7: Editing&ltbr&gt;8: UploadedToServer&ltbr&gt;10: EditingPending


