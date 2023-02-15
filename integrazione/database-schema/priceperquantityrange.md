---
description: Prezzi per scaglione quantità
---

# PricePerQuantityRange

**Chiavi**

* _Id_
* ItemId, AccountId, PriceListId, SalesUomId, UnitsPerPack, CurrencyId, StartDate, EndDate, PriceListType, SalesConditionKey, SalesAgentId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| DiscountColumn | Colonna su cui applicare gli sconti | int |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| [LockedFields](priceperquantityrange.md#lockedfields) | Campi bloccati per l'editing nei documenti | enum |  |
| NextSalesCondition | Prossima condizione di vendita da ricercare | text | 50 |
| PriceListId | Id del listino | text | 50 |
| PriceListInfo | Info listino | text | text |
| PriceListType | Tipo listino | text | 50 |
| Priority | Indica se un listino è prioritario rispetto agli altri individuati | int |  |
| QuantityRange1\_Discount1 | Sconto | dec |  |
| QuantityRange1\_Discount2 | Sconto | dec |  |
| QuantityRange1\_Discount3 | Sconto | dec |  |
| QuantityRange1\_DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| QuantityRange1\_FixedDiscount | Sconto importo | dec |  |
| [QuantityRange1\_MultipleQuantity](priceperquantityrange.md#quantityrange1_multiplequantity) | Quantità multipla | dec |  |
| QuantityRange1\_PriceListInfo | Info listino | text | text |
| QuantityRange1\_Quantity | Quantità inizio scaglione | dec |  |
| QuantityRange1\_UnitPrice | Prezzo unitario | dec |  |
| QuantityRange2\_Discount1 | Sconto | dec |  |
| QuantityRange2\_Discount2 | Sconto | dec |  |
| QuantityRange2\_Discount3 | Sconto | dec |  |
| QuantityRange2\_DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| QuantityRange2\_FixedDiscount | Sconto importo | dec |  |
| [QuantityRange2\_MultipleQuantity](priceperquantityrange.md#quantityrange2_multiplequantity) | Quantità multipla | dec |  |
| QuantityRange2\_PriceListInfo | Info listino | text | text |
| QuantityRange2\_Quantity | Quantità inizio scaglione | dec |  |
| QuantityRange2\_UnitPrice | Prezzo unitario | dec |  |
| QuantityRange3\_Discount1 | Sconto | dec |  |
| QuantityRange3\_Discount2 | Sconto | dec |  |
| QuantityRange3\_Discount3 | Sconto | dec |  |
| QuantityRange3\_DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| QuantityRange3\_FixedDiscount | Sconto importo | dec |  |
| [QuantityRange3\_MultipleQuantity](priceperquantityrange.md#quantityrange3_multiplequantity) | Quantità multipla | dec |  |
| QuantityRange3\_PriceListInfo | Info listino | text | text |
| QuantityRange3\_Quantity | Quantità inizio scaglione | dec |  |
| QuantityRange3\_UnitPrice | Prezzo unitario | dec |  |
| QuantityRange4\_Discount1 | Sconto | dec |  |
| QuantityRange4\_Discount2 | Sconto | dec |  |
| QuantityRange4\_Discount3 | Sconto | dec |  |
| QuantityRange4\_DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| QuantityRange4\_FixedDiscount | Sconto importo | dec |  |
| [QuantityRange4\_MultipleQuantity](priceperquantityrange.md#quantityrange4_multiplequantity) | Quantità multipla | dec |  |
| QuantityRange4\_PriceListInfo | Info listino | text | text |
| QuantityRange4\_Quantity | Quantità inizio scaglione | dec |  |
| QuantityRange4\_UnitPrice | Prezzo unitario | dec |  |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesConditionKey | Chiave della condizione di vendita | text | 300 |
| SalesUomId | Id unità di misura di vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| Stop | Indica se fermarsi nella ricerca delle condizioni di vendita | int |  |
| UnitsPerPack | Unità per confezione | dec |  |

## LockedFields

* 0: None
* 1: UnitPrice
* 2: Discounts
* 4: SaleType
* 8: PriceList
* 16: QuantitiesAndUom
* 32: Delete
* 64: LineDuplication

## QuantityRange1\_MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## QuantityRange2\_MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## QuantityRange3\_MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## QuantityRange4\_MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...
.