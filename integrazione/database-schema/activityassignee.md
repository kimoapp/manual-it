---
description: Utenti a cui è stata assegnata l'attività
---

# ActivityAssignee

**Chiavi**

* _Id_
* ActivityId, AssigneeId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| ActivityId | Id dell'attività | text | 50 |
| AssigneeId | Id dell'assegnatario | text | 50 |
| [AssigneeType](activityassignee.md#assigneetype) | Tipo dell'assegnatario | enum |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| SyncReference | Riferimento | text | 50 |
## AssigneeType

1. User

