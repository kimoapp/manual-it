# NavSalesPrice

<br>
**Chiavi**
- *Id*
- ItemId, SeasonId, ConstantVariableId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, SalesType, SalesCode, UomId, CurrencyId, StartDate, EndDate, StartQuantityRange, EndQuantityRange, SalesDocumentType, SalesDocumentCode
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| AllowInvoiceDiscount | Indica se sono permessi gli sconti fattura | bool |  |  |
| AllowLineDiscount | Indica se sono permessi gli sconti a livello di riga ordine | bool |  |  |
| ConstantVariableId | Id variante costante | text | 50 |  |
| CurrencyId | Id della valuta | text | 50 |  |
| EndDate | Data fine validità | date |  |  |
| EndQuantityRange | Fine scaglione quantità | dec |  |  |
| FindNext | Usato in Dynamics AX | enum |  | 0: No, 1: Yes |
| Id | Id | text | 50 |  |
| ItemId | Id dell'articolo | text | 50 |  |
| PriceIncludesVat | Indica se il prezzo è compreso di IVA | bool |  |  |
| PriceListInfo | Info listino | text | text |  |
| PricePerQtyMultiplier | Moltiplicatore prezzi per quantità | dec |  |  |
| RecId | Usato in Dynamics AX | text | 50 |  |
| SalesCode | Codice vendita | text | 50 |  |
| SalesDocumentCode | Codice categoria documento | text | 50 |  |
| SalesDocumentType | Tipo categoria documento | enum |  | 0: AllDocuments, 1: Document |
| SalesType | Tipo vendita | enum |  | 0: Customer, 1: CustomerDiscountGroup, 1: CustomerDiscountGroup, 2: AllCustomers, 3: Campaign |
| SeasonId | Id della stagione | text | 50 |  |
| StartDate | Data inizio validità | date |  |  |
| StartQuantityRange | Inizio scaglione quantità | dec |  |  |
| Type | Tipo | enum |  | 0: Item, 1: ItemDiscountGroup, 102: ItemGroupLevel1, 103: ItemGroupLevel2, 104: AllItems, 105: DefaultItemDiscountGroup, 106: ItemGroupLevel3, 107: ItemGroupLevel4, 108: Trademark |
| UnitPrice | Prezzo unitario | dec |  |  |
| UomId | Unità di misura | text | 50 |  |
| VariableId1 | Id variante | text | 50 |  |
| VariableId2 | Id variante | text | 50 |  |
| VariableValueId1 | Valore variante | text | 50 |  |
| VariableValueId2 | Valore variante | text | 50 |  |
| VatRateId | Id aliquota IVA | text | 50 |  |

