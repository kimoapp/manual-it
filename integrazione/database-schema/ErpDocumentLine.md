# ErpDocumentLine

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| Amount | Totale documento | dec |  |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |  |
| DeliveryDate | Data di consegna | date |  |  |
| DeliveryDateTypeId | Id del tipo consegna | text | 50 |  |
| Discount1 | Sconto | dec |  |  |
| Discount2 | Sconto | dec |  |  |
| Discount3 | Sconto | dec |  |  |
| Discount4 | Sconto | dec |  |  |
| Discount5 | Sconto | dec |  |  |
| ErpDocumentId | Id del documento a cui la riga appartiene | text | 50 |  |
| ErpStatusId1 |  | text | 50 |  |
| ErpStatusId2 |  | text | 50 |  |
| ErpStatusId3 |  | text | 50 |  |
| FixedDiscount |  | dec |  |  |
| FreeBoolean1 | Campo booleano libero | bool |  |  |
| FreeBoolean2 | Campo booleano libero | bool |  |  |
| FreeBoolean3 | Campo booleano libero | bool |  |  |
| FreeBoolean4 | Campo booleano libero | bool |  |  |
| FreeBoolean5 | Campo booleano libero | bool |  |  |
| FreeBoolean6 | Campo booleano libero | bool |  |  |
| FreeBoolean7 | Campo booleano libero | bool |  |  |
| FreeDateTime1 | Campo data libero | dt |  |  |
| FreeDateTime2 | Campo data libero | dt |  |  |
| FreeDateTime3 | Campo data libero | dt |  |  |
| FreeDecimal1 | Campo decimale libero | dec |  |  |
| FreeDecimal10 | Campo decimale libero | dec |  |  |
| FreeDecimal2 | Campo decimale libero | dec |  |  |
| FreeDecimal3 | Campo decimale libero | dec |  |  |
| FreeDecimal4 | Campo decimale libero | dec |  |  |
| FreeDecimal5 | Campo decimale libero | dec |  |  |
| FreeDecimal6 | Campo decimale libero | dec |  |  |
| FreeDecimal7 | Campo decimale libero | dec |  |  |
| FreeDecimal8 | Campo decimale libero | dec |  |  |
| FreeDecimal9 | Campo decimale libero | dec |  |  |
| FreeLookup1 | Id per dati tabellati | text | 50 |  |
| FreeLookup2 | Id per dati tabellati | text | 50 |  |
| FreeText1 | Campo testo libero | text | text |  |
| FreeText2 | Campo testo libero | text | text |  |
| FreeText3 | Campo testo libero | text | text |  |
| Id | Id della riga documento | text | 50 |  |
| IsDiscountEdited | Indica se lo sconto è stato modificato | bool |  |  |
| IsUnitPriceEdited | Identifica se il prezzo unitario è stato modificato | bool |  |  |
| ItemChargesAmount | Valore delle spese per l'articolo (RAEE, ...) | dec |  |  |
| ItemChargesTypeDescription | Descrizione delle spese per l'articolo applicate (RAEE, ...) | text | text |  |
| ItemDescription | Descrizione articolo | text | 130 |  |
| ItemId | Tipo dell'articolo | text | 50 |  |
| LineNumber | Numero riga | int |  |  |
| LineType | Tipo riga documento | enum |  | 0: Item, 1: ManualItem, 2: Note, 3: ModelItem, 4: VariableItem, 5: Idrolab |
| ManufacturerId | Id produttore | text | 50 |  |
| ManufacturerItemId | Id articolo produttore | text | 50 |  |
| NetUnitPrice | Prezzo unitario netto | dec |  |  |
| Notes | Note | text | text |  |
| NumberOfPacks | Numero confezioni | dec |  |  |
| PackUnitQty | Quantità totale espressa nell'unità di misura unitaria di imballo | dec |  |  |
| PackUnitUomId | Unità di misura unitaria di imballo | text | 20 |  |
| PackUnitUomToSalesUomQtyRatio | Rapporto di conversione tra unità di misura unitaria di imballo e unità di misura di vendita | dec |  |  |
| PackUomId | Unità di misura di imballo | text | 20 |  |
| ParentLineId | Riferimento alla riga padre | text | 50 |  |
| PriceListId | Id del listino | text | 50 |  |
| PriceListInfo | Info sul listino | text | text |  |
| RetailDiscount1 | Sconto | dec |  |  |
| RetailDiscount2 | Sconto | dec |  |  |
| RetailDiscount3 | Sconto | dec |  |  |
| RetailDiscount4 | Sconto | dec |  |  |
| RetailDiscount5 | Sconto | dec |  |  |
| RetailFixedDiscount |  | dec |  |  |
| RetailNetUnitPrice | Prezzo unitario netto retail | dec |  |  |
| RetailPriceListId | Id listino retail | text | 50 |  |
| RetailUnitPrice | prezzo unitario retail | dec |  |  |
| SalesQty | Quantità di vendita | dec |  |  |
| SalesUomId | Unità di misura di vendita | text | 10 |  |
| SaleTypeId | Tipo vendita | text | 50 |  |
| SourceReference | Numero del documento di riferimento | text | 50 |  |
| SourceReferenceType | Tipo del documento di riferimento | enum |  |  |
| UnitPrice | Prezzo unitario | dec |  |  |
| UnitsPerPack | Unità per confezione | dec |  |  |
| VariableId1 | Id variante | text | 50 |  |
| VariableId2 | Id variante | text | 50 |  |
| VariableItemId | Id articolo variante | text | 50 |  |
| VariableValueId1 | Valore variante | text | 50 |  |
| VariableValueId2 | Valore variante | text | 50 |  |
| VatAmount | Importo IVA | dec |  |  |
| VatRateId | Id | text | 50 |  |
| VatRateIsExemption | Indica se l'IVA è calcolata o no | bool |  |  |
| VatRateValue | Valore aliquota | dec |  |  |
| WarehouseId | Id del magazzino | text | 50 |  |

