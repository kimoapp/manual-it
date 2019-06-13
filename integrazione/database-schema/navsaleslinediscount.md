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
0: No<br>1: Yes
SalesType
---
0: Customer<br>1: CustomerDiscountGroup<br>1: CustomerDiscountGroup<br>2: AllCustomers<br>3: Campaign
Type
---
0: Item<br>1: ItemDiscountGroup<br>102: ItemGroupLevel1<br>103: ItemGroupLevel2<br>104: AllItems<br>105: DefaultItemDiscountGroup<br>106: ItemGroupLevel3<br>107: ItemGroupLevel4<br>108: Trademark


