---
description: Riassortimenti
---

# Reassortment

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](reassortment.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| CustomerId | Id del cliente a cui fa riferimento il riassortimento | text | 50 |
| Id | Identificativo del riassortimento | text | 50 |
| Notes | Note | text | text |
| ReassortmentTypeId | Tipo di riassortimento | text | 50 |
| ShipmentSiteId | Id della destinazione merce a cui fa riferimento il riassortimento | text | 50 |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup
