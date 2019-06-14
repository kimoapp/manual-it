---
description: Sconti nell'Erp Nav
---

# NavSalesLineDiscount

**Chiavi**

* _Id_
* Code, Type, SalesType, SalesCode, StartQuantityRange, EndQuantityRange, UomId, CurrencyId, StartDate, EndDate, VariableItemId

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
| EndQuantityRange | Fine scaglione quantità | dec |  |
| [FindNext](navsaleslinediscount.md#findnext) | Usato in Dynamics AX | enum |  |
| Id | Id | text | 50 |
| RecId | Usato in Dynamics AX | text | 50 |
| SalesCode | Codice vendita | text | 50 |
| [SalesType](navsaleslinediscount.md#salestype) | Tipo vendita | enum |  |
| SpecialPriceListId | Listino speciale | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio scaglione quantità | dec |  |
| [Type](navsaleslinediscount.md#type) | Tipo sconto | enum |  |
| UomId | Unità di misura | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
## FindNext

* 0: No
* 1: Yes

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


