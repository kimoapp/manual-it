---
description: Righe dei Documenti da Erp
---

# ErpDocumentLine

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Amount | Totale documento | dec |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |
| DeliveryDate | Data di consegna | date |  |
| DeliveryDateTypeId | Id del tipo consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| Discount5 | Sconto | dec |  |
| Discount6 | Sconto | dec |  |
| Discount7 | Sconto | dec |  |
| ErpDocumentId | Id del documento a cui la riga appartiene | text | 50 |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| ExpiryDate |  | date |  |
| FixedDiscount |  | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeBoolean6 | Campo booleano libero | bool |  |
| FreeBoolean7 | Campo booleano libero | bool |  |
| FreeDateTime1 | Campo data libero | dt |  |
| FreeDateTime2 | Campo data libero | dt |  |
| FreeDateTime3 | Campo data libero | dt |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal10 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeDecimal4 | Campo decimale libero | dec |  |
| FreeDecimal5 | Campo decimale libero | dec |  |
| FreeDecimal6 | Campo decimale libero | dec |  |
| FreeDecimal7 | Campo decimale libero | dec |  |
| FreeDecimal8 | Campo decimale libero | dec |  |
| FreeDecimal9 | Campo decimale libero | dec |  |
| FreeLookup1 | Id per dati tabellati | text | 50 |
| FreeLookup2 | Id per dati tabellati | text | 50 |
| FreeLookup3 | Id per dati tabellati | text | 50 |
| FreeLookup4 | Id per dati tabellati | text | 50 |
| FreeLookup5 | Id per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FreeText4 | Campo testo libero | text | text |
| FreeText5 | Campo testo libero | text | text |
| FulfillmentDate | Data disponibilità merce | date |  |
| [FulfillmentStatus](erpdocumentline.md#fulfillmentstatus) | Stato evasione riga documento | enum |  |
| GrossCost | Costo lordo | dec |  |
| Id | Id della riga documento | text | 50 |
| [InPromotion](erpdocumentline.md#inpromotion) | In promozione | enum |  |
| IsDiscountEdited | Indica se lo sconto è stato modificato | bool |  |
| IsUnitPriceEdited | Identifica se il prezzo unitario è stato modificato | bool |  |
| ItemChargesAmount | Valore delle spese per l'articolo \(RAEE, ...\) | dec |  |
| ItemChargesTypeDescription | Descrizione delle spese per l'articolo applicate \(RAEE, ...\) | text | text |
| ItemCollectionId | Id della collezione | text | 50 |
| ItemDescription | Descrizione articolo | text | 130 |
| ItemDiscountGroupId | Id del gruppo sconti articolo | text | 50 |
| ItemGenderId | Id genere | text | 50 |
| ItemId | Tipo dell'articolo | text | 50 |
| ItemLineId | Id della linea | text | 50 |
| ItemSeriesId | Id serie articolo | text | 50 |
| LineMarkup | Ricarico percentuale | dec |  |
| LineMarkupAmount | Ricarico in valore | dec |  |
| LineMarkupAmountOnNetCost | Margine in valore | dec |  |
| LineMarkupOnNetCost | Margine percentuale | dec |  |
| LineNumber | Numero riga | int |  |
| [LineType](erpdocumentline.md#linetype) | Tipo riga documento | enum |  |
| Lot | Lotto | text | 50 |
| LotDate |  | date |  |
| ManufacturerId | Id produttore | text | 50 |
| ManufacturerItemId | Id articolo produttore | text | 50 |
| NetCost | Costo netto | dec |  |
| NetUnitPrice | Prezzo unitario netto | dec |  |
| Notes | Note | text | text |
| NumberOfPacks | Numero confezioni | dec |  |
| OutstandingQty | Quantità rimanente | dec |  |
| PackUnitQty | Quantità totale espressa nell'unità di misura unitaria di imballo | dec |  |
| PackUnitUomId | Unità di misura unitaria di imballo | text | 20 |
| PackUnitUomToSalesUomQtyRatio | Rapporto di conversione tra unità di misura unitaria di imballo e unità di misura di vendita | dec |  |
| PackUomId | Unità di misura di imballo | text | 20 |
| ParentLineId | Riferimento alla riga padre | text | 50 |
| PriceListId | Id del listino | text | 50 |
| PriceListInfo | Info sul listino | text | text |
| ProductionDate |  | date |  |
| PromotionDescription | Descrizione promozione | text | text |
| RetailDiscount1 | Sconto | dec |  |
| RetailDiscount2 | Sconto | dec |  |
| RetailDiscount3 | Sconto | dec |  |
| RetailDiscount4 | Sconto | dec |  |
| RetailDiscount5 | Sconto | dec |  |
| RetailDiscount6 | Sconto | dec |  |
| RetailDiscount7 | Sconto | dec |  |
| RetailFixedDiscount |  | dec |  |
| RetailNetUnitPrice | Prezzo unitario netto retail | dec |  |
| RetailPriceListId | Id listino retail | text | 50 |
| RetailUnitPrice | prezzo unitario retail | dec |  |
| SalesQty | Quantità di vendita | dec |  |
| SalesUomId | Unità di misura di vendita | text | 10 |
| SaleTypeId | Tipo vendita | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| ShippedQty | Quantità consegnata | dec |  |
| SourceReference | Numero del documento di riferimento | text | 50 |
| SourceReferenceType | Tipo del documento di riferimento | enum |  |
| StatisticReferenceDate | Data di riferimento per le statistiche tramite smart BI | date |  |
| TrademarkId | Id del marchio | text | 50 |
| UnitPrice | Prezzo unitario | dec |  |
| UnitsPerPack | Unità per confezione | dec |  |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableItemId | Id articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |
| VatAmount | Importo IVA | dec |  |
| VatRateId | Id | text | 50 |
| VatRateIsExemption | Indica se l'IVA è calcolata o no | bool |  |
| VatRateValue | Valore aliquota | dec |  |
| WarehouseId | Id del magazzino | text | 50 |

## FulfillmentStatus

* 0: Undefined
* 1: NotStarted
* 2: Partial
* 3: Completed
* 4: ForcedComplete

## InPromotion

* 0: No
* 1: Yes

## LineType

* 0: Item
* 1: ManualItem
* 2: Note
* 3: ModelItem
* 4: VariableItem
* 5: Idrolab
