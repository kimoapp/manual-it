---
description: Prezzi di vendita nell'Erp SAP S/4HANA
---

# SapS4HanaPrice

**Chiavi**

* _Id_
* ConditionType, ConditionTable, ConditionSequentialNumber, AccountId, ItemId, CustomerPriceGroupId, DocumentTypeId, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ConditionKey |  | text | 50 |
| ConditionSequentialNumber |  | int |  |
| ConditionTable |  | text | 50 |
| ConditionType |  | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerPriceGroupId | Id del gruppo prezzi cliente | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| Id | Id | text | 50 |
| [IgnoreDiscounts](saps4hanaprice.md#ignorediscounts) | Ignora gli sconti | enum |  |
| ItemId | Id dell'articolo | text | 50 |
| [LockedFields](saps4hanaprice.md#lockedfields) | Campi bloccati per l'editing nei documenti | enum |  |
| [MultipleQuantity](saps4hanaprice.md#multiplequantity) | Quantità multipla | dec |  |
| [PaymentMethodDiscountsMode](saps4hanaprice.md#paymentmethoddiscountsmode) | Modalità di gestione dello sconto finanziario | enum |  |
| PriceListInfo | Info listino | text | text |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| UnitPrice | Prezzo unitario | dec |  |
| UomId | Unità di misura | text | 50 |

## IgnoreDiscounts

* 0: No
* 1: Yes

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

## PaymentMethodDiscountsMode

* 0: Default
* 1: Ignore
