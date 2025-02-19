---
description: Spese per articoli
---

# ItemCharge

**Chiavi**

* _Id_
* ItemChargeTypeId, ItemId, AccountEncodingKey, StartDate, EndDate, CurrencyId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](itemcharge.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ItemChargeTypeId | Id del tipo di spesa | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| StartDate | Data inizio validità | date |  |
| Value | Valore spesa dell'articolo | dec |  |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup
