# ActivityAssignee

Utenti a cui è stata assegnata l'attività

<br>
**Chiavi**
- *Id*
- ActivityId, AssigneeId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| ActivityId | Id dell'attività | text | 50 |
| AssigneeId | Id dell'assegnatario | text | 50 |
| [AssigneeType](#assigneetype) | Tipo dell'assegnatario | enum |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| SyncReference | Riferimento | text | 50 |

AssigneeType
---
1: User

