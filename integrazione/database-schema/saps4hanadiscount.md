---
description: Sconti nell'Erp SAP S/4HANA
---

# SapS4HanaDiscount

**Chiavi**

* _Id_
* ConditionType, ConditionTable, ConditionSequentialNumber, AccountId, CustomerDiscountGroupId, ItemId, ItemGroupLevel1Id, ItemGroupLevel2Id, ItemGroupLevel3Id, ItemGroupLevel4Id, ItemSeriesId, ItemDiscountGroupId, ItemLineId, DocumentTypeId, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ConditionKey |  | text | 50 |
| ConditionSequentialNumber |  | int |  |
| ConditionTable |  | text | 50 |
| ConditionType |  | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerDiscountGroupId | Id del gruppo sconti cliente | text | 50 |
| Discount | Sconto | dec |  |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| Id | Id | text | 50 |
| ItemDiscountGroupId | Id del gruppo sconti articolo | text | 50 |
| ItemGroupLevel1Id | Id gruppo articoli livello 1 | text | 50 |
| ItemGroupLevel2Id | Id gruppo articoli livello 2 | text | 50 |
| ItemGroupLevel3Id | Id gruppo articoli livello 3 | text | 50 |
| ItemGroupLevel4Id | Id gruppo articoli livello 4 | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| ItemLineId | Id della linea | text | 50 |
| ItemSeriesId | Id serie articolo | text | 50 |
| [LockedFields](saps4hanadiscount.md#lockedfields) | Campi bloccati per l'editing nei documenti | enum |  |
| [MultipleQuantity](saps4hanadiscount.md#multiplequantity) | Quantità multipla | dec |  |
| PriceListInfo | Info listino | text | text |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| UomId | Unità di misura | text | 50 |

## LockedFields

* 0: None
* 1: UnitPrice
* 2: Discounts
* 4: SaleType
* 8: PriceList
* 16: QuantitiesAndUom
* 32: Delete
* 64: LineDuplication

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...
