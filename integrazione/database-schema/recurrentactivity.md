# RecurrentActivity

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| AccountId | Id del cliente | text | 50 |  |
| ActivityTypeId | Id del tipo attività | text | 50 |  |
| ContactId | Contatto | text | 50 |  |
| CreationDate | Data di creazione | dt |  |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |  |
| Duration |  | int |  |  |
| EntityStatus | Campo che definisce lo stato del record | enum |  | 0: ImportedFromErp, 1: ExportedToErp, 2: ImportedByErp, 3: ExportingToErp, 4: Deleted, 5: CommittingExportToErp, 6: ToExportToErp, 7: Editing, 8: UploadedToServer |
| FreeBoolean1 | Campo booleano libero | bool |  |  |
| FreeBoolean2 | Campo booleano libero | bool |  |  |
| FreeBoolean3 | Campo booleano libero | bool |  |  |
| FreeBoolean4 | Campo booleano libero | bool |  |  |
| FreeBoolean5 | Campo booleano libero | bool |  |  |
| FreeBoolean6 | Campo booleano libero | bool |  |  |
| FreeBoolean7 | Campo booleano libero | bool |  |  |
| FreeContextLookup1 | Id per dato tabellato legato al contesto | text | 50 |  |
| FreeContextLookup2 | Id per dato tabellato legato al contesto | text | 50 |  |
| FreeContextLookup3 | Id per dato tabellato legato al contesto | text | 50 |  |
| FreeContextLookup4 | Id per dato tabellato legato al contesto | text | 50 |  |
| FreeContextLookup5 | Id per dato tabellato legato al contesto | text | 50 |  |
| FreeDecimal1 | Campo decimale libero | dec |  |  |
| FreeDecimal2 | Campo decimale libero | dec |  |  |
| FreeDecimal3 | Campo decimale libero | dec |  |  |
| FreeLookup1 | Id per dato tabellato | text | 50 |  |
| FreeLookup2 | Id per dato tabellato | text | 50 |  |
| FreeLookup3 | Id per dato tabellato | text | 50 |  |
| FreeText1 | Campo testo libero | text | text |  |
| FreeText2 | Campo testo libero | text | text |  |
| FreeText3 | Campo testo libero | text | text |  |
| FreeText4 | Campo testo libero | text | text |  |
| FreeText5 | Campo testo libero | text | text |  |
| Id | Id | text | 50 |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |  |
| Notes | Note | text | text |  |
| RecurrenceDaysOfWeek | Giorno della settimana in cui viene svolta l'attività | enum |  | 1: Monday, 2: Tuesday, 4: Wednesday, 8: Thurdsay, 16: Friday, 32: Saturday, 64: Sunday |
| RecurrenceEndDate | Data fine | dt |  |  |
| RecurrenceFrequency | Frequenza | int |  |  |
| RecurrenceStartDate | Data inizio | dt |  |  |
| RecurrenceStatus | Stato | enum |  | 0: Undefined, 1: Active, 2: Suspended |
| RecurrenceType | Tipo | enum |  | 1: Weekly, 2: Daily, 3: Monthly, 4: OneTime |
| RelatedEntityDescription | Descrizione dell'entità collegata | text | text |  |
| RelatedEntityId | Id dell'entità collegata | text | 50 |  |
| RelatedEntityType | Tipo dell'entità collegata | enum |  | 0: Undefined, 1: ErpDocument, 2: Document, 3: BudgetLine |
| RelatedEntityTypeId | Id del tipo dell'entità collegata | text | 50 |  |
| SeasonId | Id della stagione | text | 50 |  |
| Subject | Oggetto | text | text |  |
| SyncReference | Riferimento | text | 50 |  |
| TrademarkId | Id del marchio | text | 50 |  |
| UploadToServerTimeStamp |  | dt |  |  |

