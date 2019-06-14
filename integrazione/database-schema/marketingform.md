---
description: Schede Marketing
---

# MarketingForm

**Chiavi**

* _Id_
* AccountId, FormTypeId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| [EntityStatus](marketingform.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| FormFamilyId | Id della famiglia della scheda marketing | text | 50 |
| FormTypeId | Id del tipo di scheda marketing | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| RegistryTypeId | Id del tipo di registrazione | text | 50 |
| SyncReference | Riferimento | text | 50 |
| UploadToServerTimeStamp |  | dt |  |

## EntityStatus

0: ImportedFromErp&lt;br&gt;1: ExportedToErp&lt;br&gt;2: ImportedByErp&lt;br&gt;3: ExportingToErp&lt;br&gt;4: Deleted&lt;br&gt;5: CommittingExportToErp&lt;br&gt;6: ToExportToErp&lt;br&gt;7: Editing&lt;br&gt;8: UploadedToServer&lt;br&gt;10: EditingPending

