---
description: Sconti nell'Erp Nav
---

# NavSalesLineDiscount

**Chiavi**

* _Id_
* Code, Type, SalesType, SalesCode, StartQuantityRange, EndQuantityRange, UomId, CurrencyId, StartDate, EndDate, VariableItemId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, SalesAgentId, RecId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Code | Codice sconto | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| Discount5 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| [FindNext](navsaleslinediscount.md#findnext) | Usato in Dynamics AX | enum |  |
| Id | Id | text | 50 |
| [MultipleQuantity](navsaleslinediscount.md#multiplequantity) | Quantità multipla | dec |  |
| PriceListInfo | Info listino | text | text |
| RecId | Usato in Dynamics AX | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesCode | Codice vendita | text | 50 |
| [SalesType](navsaleslinediscount.md#salestype) | Tipo vendita | enum |  |
| SpecialPriceListId | Listino speciale | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| [Type](navsaleslinediscount.md#type) | Tipo sconto | enum |  |
| UomId | Unità di misura | text | 50 |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |

## FindNext

* 0: No
* 1: Yes

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## SalesType

* 0: Customer
* 1: CustomerDiscountGroup
* 1: CustomerDiscountGroup
* 2: AllCustomers
* 3: Campaign

## Type

* 0: Item
* 1: ItemDiscountGroup
* 102: ItemGroupLevel1
* 103: ItemGroupLevel2
* 104: AllItems
* 105: DefaultItemDiscountGroup
* 106: ItemGroupLevel3
* 107: ItemGroupLevel4
* 108: Trademark
* 109: ItemSeries
* 110: ItemCollection
* 111: ItemLine
* 112: ItemSeries\_And\_ItemLine
* 113: ItemCollection\_And\_ItemLine
