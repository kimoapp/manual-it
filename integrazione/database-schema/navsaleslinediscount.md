---
description: Sconti nell'Erp Nav
---
# NavSalesLineDiscount

<br>
**Chiavi**
- *Id*
- Code, Type, SalesType, SalesCode, StartQuantityRange, EndQuantityRange, UomId, CurrencyId, StartDate, EndDate, VariableItemId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| Code | Codice sconto | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| Discount5 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine scaglione quantità | dec |  |
| [FindNext](#findnext) | Usato in Dynamics AX | enum |  |
| Id | Id | text | 50 |
| RecId | Usato in Dynamics AX | text | 50 |
| SalesCode | Codice vendita | text | 50 |
| [SalesType](#salestype) | Tipo vendita | enum |  |
| SpecialPriceListId | Listino speciale | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio scaglione quantità | dec |  |
| [Type](#type) | Tipo sconto | enum |  |
| UomId | Unità di misura | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |

FindNext
---
0: No&ltbr&gt;1: Yes
SalesType
---
0: Customer&ltbr&gt;1: CustomerDiscountGroup&ltbr&gt;1: CustomerDiscountGroup&ltbr&gt;2: AllCustomers&ltbr&gt;3: Campaign
Type
---
0: Item&ltbr&gt;1: ItemDiscountGroup&ltbr&gt;102: ItemGroupLevel1&ltbr&gt;103: ItemGroupLevel2&ltbr&gt;104: AllItems&ltbr&gt;105: DefaultItemDiscountGroup&ltbr&gt;106: ItemGroupLevel3&ltbr&gt;107: ItemGroupLevel4&ltbr&gt;108: Trademark


