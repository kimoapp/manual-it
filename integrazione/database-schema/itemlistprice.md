---
description: Prezzi per articolo
---

# ItemListPrice

**Chiavi**

* _Id_
* ItemId, AccountId, PriceListId, SalesUomId, UnitsPerPack, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange, PriceListType, SalesConditionKey, SalesAgentId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| Discount5 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| FixedDiscount | Sconto importo | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id | text | 50 |
| [IgnoreDiscounts](itemlistprice.md#ignorediscounts) |  | enum |  |
| ItemId | Id dell'articolo | text | 50 |
| [LockedFields](itemlistprice.md#lockedfields) | Campi bloccati per l'editing nei documenti | enum |  |
| PriceListId | Id del listino | text | 50 |
| PriceListInfo | Info listino | text | text |
| PriceListType | Tipo listino | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesConditionKey | Chiave della condizione di vendita | text | 300 |
| SalesUomId | Id unità di misura di vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| UnitPrice | Prezzo unitario | dec |  |
| UnitsPerPack | Unità per confezione | dec |  |

## IgnoreDiscounts

0: No 1: Yes

## LockedFields

0: None 1: UnitPrice 2: Discounts 4: SaleType

