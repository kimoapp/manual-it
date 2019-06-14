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

1. ImportedFromErp
2. ExportedToErp
3. ImportedByErp
4. ExportingToErp
5. Deleted
6. CommittingExportToErp
7. ToExportToErp
8. Editing
9. UploadedToServer
10. EditingPending

