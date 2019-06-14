---
description: Attività
---

# Activity

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ActivityTypeId | Id del tipo attività | text | 50 |
| ContactId | Contatto | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Duration |  | int |  |
| EndDate | Data fine attività | dt |  |
| [EntityStatus](activity.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| Expiration | Data fine attività | dt |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeBoolean6 | Campo booleano libero | bool |  |
| FreeBoolean7 | Campo booleano libero | bool |  |
| FreeContextLookup1 | Id per dato tabellato legato al contesto | text | 50 |
| FreeContextLookup2 | Id per dato tabellato legato al contesto | text | 50 |
| FreeContextLookup3 | Id per dato tabellato legato al contesto | text | 50 |
| FreeContextLookup4 | Id per dato tabellato legato al contesto | text | 50 |
| FreeContextLookup5 | Id per dato tabellato legato al contesto | text | 50 |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeLookup1 | Id per dato tabellato | text | 50 |
| FreeLookup2 | Id per dato tabellato | text | 50 |
| FreeLookup3 | Id per dato tabellato | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FreeText4 | Campo testo libero | text | text |
| FreeText5 | Campo testo libero | text | text |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| Notes | Note | text | text |
| RecurrenceDate | Data dell'attività schedulata dal quale è stata generata l'attività | date |  |
| RecurrenceId | Id dell'attività schedulata dal quale è stata generata l'attività | text | 50 |
| RelatedEntityDescription | Descrizione dell'entità collegata | text | text |
| RelatedEntityId | Id dell'entità collegata | text | 50 |
| [RelatedEntityType](activity.md#relatedentitytype) | Tipo dell'entità collegata | enum |  |
| RelatedEntityTypeId | Id del tipo dell'entità collegata | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| StartDate | Data inizio attività | dt |  |
| [Status](activity.md#status) | Stato dell'attività | enum |  |
| Subject | Oggetto | text | text |
| SyncReference | Riferimento | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| UploadToServerTimeStamp |  | dt |  |
## EntityStatus

0: ImportedFromErp
1: ExportedToErp
2: ImportedByErp
3: ExportingToErp
4: Deleted
5: CommittingExportToErp
6: ToExportToErp
7: Editing
8: UploadedToServer
10: EditingPending
## RelatedEntityType

0: Undefined
1: ErpDocument
2: Document
3: BudgetLine
## Status

0: Undefined
1: Open
2: Completed
3: Expired
4: Late
5: Dismissed
1000: FromRecurrence

