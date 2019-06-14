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

1. No
2. Yes

   **SalesType**

3. Customer
4. CustomerDiscountGroup
5. CustomerDiscountGroup
6. AllCustomers
7. Campaign

   **Type**

8. Item
9. ItemDiscountGroup
10. ItemGroupLevel1
11. ItemGroupLevel2
12. AllItems
13. DefaultItemDiscountGroup
14. ItemGroupLevel3
15. ItemGroupLevel4
16. Trademark

