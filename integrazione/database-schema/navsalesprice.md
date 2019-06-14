---
description: Prezzi di vendita nell'Erp Nav
---

# NavSalesPrice

**Chiavi**

* _Id_
* ItemId, SeasonId, ConstantVariableId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, SalesType, SalesCode, UomId, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange, SalesDocumentType, SalesDocumentCode

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AllowInvoiceDiscount | Indica se sono permessi gli sconti fattura | bool |  |
| AllowLineDiscount | Indica se sono permessi gli sconti a livello di riga ordine | bool |  |
| ConstantVariableId | Id variante costante | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine scaglione quantità | dec |  |
| [FindNext](navsalesprice.md#findnext) | Usato in Dynamics AX | enum |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| PriceIncludesVat | Indica se il prezzo è compreso di IVA | bool |  |
| PriceListInfo | Info listino | text | text |
| PricePerQtyMultiplier | Moltiplicatore prezzi per quantità | dec |  |
| RecId | Usato in Dynamics AX | text | 50 |
| SalesCode | Codice vendita | text | 50 |
| SalesDocumentCode | Codice categoria documento | text | 50 |
| [SalesDocumentType](navsalesprice.md#salesdocumenttype) | Tipo categoria documento | enum |  |
| [SalesType](navsalesprice.md#salestype) | Tipo vendita | enum |  |
| SeasonId | Id della stagione | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio scaglione quantità | dec |  |
| [Type](navsalesprice.md#type) | Tipo | enum |  |
| UnitPrice | Prezzo unitario | dec |  |
| UomId | Unità di misura | text | 50 |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |
| VatRateId | Id aliquota IVA | text | 50 |

## FindNext

0: No&lt;br&gt;1: Yes

## SalesDocumentType

0: AllDocuments&lt;br&gt;1: Document

## SalesType

0: Customer&lt;br&gt;1: CustomerDiscountGroup&lt;br&gt;1: CustomerDiscountGroup&lt;br&gt;2: AllCustomers&lt;br&gt;3: Campaign

## Type

0: Item&lt;br&gt;1: ItemDiscountGroup&lt;br&gt;102: ItemGroupLevel1&lt;br&gt;103: ItemGroupLevel2&lt;br&gt;104: AllItems&lt;br&gt;105: DefaultItemDiscountGroup&lt;br&gt;106: ItemGroupLevel3&lt;br&gt;107: ItemGroupLevel4&lt;br&gt;108: Trademark

