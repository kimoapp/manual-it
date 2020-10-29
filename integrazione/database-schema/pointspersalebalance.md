---
description: Saldo punti vendita
---

# PointsPerSaleBalance

**Chiavi**

* _Id_
* AccountEncodingType, AccountEncodingKey, SalesAgentId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](pointspersalebalance.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| Id | Id | text | 50 |
| Points | Punti | dec |  |
| SalesAgentId | Id dell'agente | text | 50 |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup

