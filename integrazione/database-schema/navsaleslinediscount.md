---
description: Sconti nell'Erp Nav
---
# NavSalesLineDiscount

**Chiavi**

- *Id*
- Code, Type, SalesType, SalesCode, StartQuantityRange, EndQuantityRange, UomId, CurrencyId, StartDate, EndDate, VariableItemId

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

0: No&lt;br&gt;1: Yes
## SalesType

0: Customer&lt;br&gt;1: CustomerDiscountGroup&lt;br&gt;1: CustomerDiscountGroup&lt;br&gt;2: AllCustomers&lt;br&gt;3: Campaign
## Type

0: Item&lt;br&gt;1: ItemDiscountGroup&lt;br&gt;102: ItemGroupLevel1&lt;br&gt;103: ItemGroupLevel2&lt;br&gt;104: AllItems&lt;br&gt;105: DefaultItemDiscountGroup&lt;br&gt;106: ItemGroupLevel3&lt;br&gt;107: ItemGroupLevel4&lt;br&gt;108: Trademark


