# NavSalesPrice
Prezzi di vendita nell'Erp Nav

<br>
**Chiavi**
- *Id*
- ItemId, SeasonId, ConstantVariableId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, SalesType, SalesCode, UomId, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange, SalesDocumentType, SalesDocumentCode
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| AllowInvoiceDiscount | Indica se sono permessi gli sconti fattura | bool |  |
| AllowLineDiscount | Indica se sono permessi gli sconti a livello di riga ordine | bool |  |
| ConstantVariableId | Id variante costante | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine scaglione quantità | dec |  |
| [FindNext](#findnext) | Usato in Dynamics AX | enum |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| PriceIncludesVat | Indica se il prezzo è compreso di IVA | bool |  |
| PriceListInfo | Info listino | text | text |
| PricePerQtyMultiplier | Moltiplicatore prezzi per quantità | dec |  |
| RecId | Usato in Dynamics AX | text | 50 |
| SalesCode | Codice vendita | text | 50 |
| SalesDocumentCode | Codice categoria documento | text | 50 |
| [SalesDocumentType](#salesdocumenttype) | Tipo categoria documento | enum |  |
| [SalesType](#salestype) | Tipo vendita | enum |  |
| SeasonId | Id della stagione | text | 50 |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio scaglione quantità | dec |  |
| [Type](#type) | Tipo | enum |  |
| UnitPrice | Prezzo unitario | dec |  |
| UomId | Unità di misura | text | 50 |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |
| VatRateId | Id aliquota IVA | text | 50 |

FindNext
---
0: No<br>1: Yes
SalesDocumentType
---
0: AllDocuments<br>1: Document
SalesType
---
0: Customer<br>1: CustomerDiscountGroup<br>1: CustomerDiscountGroup<br>2: AllCustomers<br>3: Campaign
Type
---
0: Item<br>1: ItemDiscountGroup<br>102: ItemGroupLevel1<br>103: ItemGroupLevel2<br>104: AllItems<br>105: DefaultItemDiscountGroup<br>106: ItemGroupLevel3<br>107: ItemGroupLevel4<br>108: Trademark

