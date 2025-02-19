---
description: Contatti per opportunità
---

# ContactPerOpportunity

**Chiavi**

* _Id_
* ContactId, OpportunityId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| ContactId | Codice contatto | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| [LeaderType](contactperopportunity.md#leadertype) | Tipo di leader | enum |  |
| OpportunityId | Codice opportunità | text | 50 |
| SyncReference | Riferimento | text | 50 |

## LeaderType

* 0: Undefined
* 1: HiddenLeader
* 2: KnownLeader
