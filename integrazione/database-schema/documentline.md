---
description: 
---

# DocumentLine

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Amount | Totale documento | dec |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |
| [AvailabilityMode](documentline.md#availabilitymode) | Modalità disponibilità | enum |  |
| AvailabilityRuleId | Id della regola di disponibilità | text | 50 |
| [ChargeForUnpackaged](documentline.md#chargeforunpackaged) | Addebita fuori confezione \(sfusi\) | enum |  |
| CheckoutAvailabilityAsFreeText | Campo testo libero in cui riportare la disponibilità strutturata come richiesto dal cliente | text | text |
| CheckoutGlobalAvailability | Disponibilità Globale | dec |  |
| CheckoutLogisticCenterAvailability | Disponibilità Polo Logistico | dec |  |
| CheckoutWarehouseAvailability | Disponibilità Magazzino | dec |  |
| CollectOnSite | Ritiro in sede \(al banco\) della merce | bool |  |
| CollectOnSiteDateTime | Data/ora del ritiro della merce | date |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| CustomerGroupId | Id del gruppo cliente | text | 50 |
| DeliveryDate | Data consegna | date |  |
| DeliveryDateTypeId | Tipo data di consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| Discount5 | Sconto | dec |  |
| Discount6 | Sconto | dec |  |
| Discount7 | Sconto | dec |  |
| DiscountOnGrossCost | Sconto sul costo lordo | dec |  |
| DocumentId | Id del documento | text | 50 |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| EndShipmentDate | Fine data spedizione | date |  |
| ExpiryDate |  | date |  |
| FixedDiscount |  | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeBoolean6 | Campo booleano libero | bool |  |
| FreeBoolean7 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeLookup1 | Id per dati tabellati | text | 50 |
| FreeLookup2 | Id per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FulfillmentDate | Data evadibilità | date |  |
| FulfillmentStatus | Stato evadibilità | enum |  |
| GrossCost | Costo lordo | dec |  |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| IsDiscountEdited | Indica se lo sconto è stato modificato | bool |  |
| IsUnitPriceEdited | Indica se il prezzo unitario è stato modificato | bool |  |
| ItemChargesAmount | Valore delle spese per l'articolo \(RAEE, ...\) | dec |  |
| ItemChargesTypeDescription | Descrizione delle spese per l'articolo applicate \(RAEE, ...\) | text | text |
| ItemDescription | Descrizione articolo | text | 130 |
| ItemDiscountGroupId | Id del gruppo sconti articolo | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| LineMarkup | Ricarico | dec |  |
| LineMarkupOnNetCost | Margine | dec |  |
| LineNumber | Riga documento | int |  |
| [LineStatus](documentline.md#linestatus) | Stato della riga | enum |  |
| [LineType](documentline.md#linetype) | Tipo riga | enum |  |
| LoseRemaining | Perdita residuo | bool |  |
| Lot | Lotto | text | 50 |
| LotDate |  | date |  |
| ManufacturerId | Id del produttore | text | 50 |
| ManufacturerItemId | Id dell'articolo produttore | text | 50 |
| [MultipleQuantity](documentline.md#multiplequantity) | Quantità multipla | dec |  |
| NetCost | Costo netto | dec |  |
| NetUnitPrice | Prezzo unitario netto | dec |  |
| Notes | Note | text | text |
| NumberOfPacks | Numero confezioni | dec |  |
| OriginalDiscount1 | Sconto | dec |  |
| OriginalDiscount2 | Sconto | dec |  |
| OriginalDiscount3 | Sconto | dec |  |
| OriginalDiscount4 | Sconto | dec |  |
| OriginalDiscount5 | Sconto | dec |  |
| OriginalDiscount6 | Sconto | dec |  |
| OriginalDiscount7 | Sconto | dec |  |
| OriginalFixedDiscount |  | dec |  |
| OriginalNetUnitPrice | Prezzo unitario netto \(originale\) | dec |  |
| OriginalPriceIncludesVat | Indica se il prezzo è ivato \(originale\) | bool |  |
| OriginalPriceListId | Id listino \(originale\) | text | 50 |
| OriginalPriceListInfo | Info listino \(originale\) | text | text |
| OriginalUnitPrice | Prezzo unitario \(originale\) | dec |  |
| PackUnitQty | Quantità espressa nell'unità di misura unitaria d'imballo | dec |  |
| PackUnitUomId | Unità di misura unitaria d'imballo | text | 20 |
| PackUnitUomToSalesUomQtyRatio | Rapporto di conversione da unità di misura unitaria d'imballo a unità di misura di vendita | dec |  |
| PackUomId | Unità di misura d'imballo | text | 20 |
| ParentLineId | Id riga padre | text | 50 |
| PointsPerSale | Punti per la vendita | dec |  |
| PriceIncludesVat | Indica se il prezzo è ivato | bool |  |
| PriceListId | Id listino | text | 50 |
| PriceListInfo | Info listino | text | text |
| PricePerQtyMultiplier |  | dec |  |
| [PriceRecalculationStatus](documentline.md#pricerecalculationstatus) | Stato del ricalcolo dei prezzi | enum |  |
| ProductionDate |  | date |  |
| PromotionActivationGroupId | Id della promozione | text | 50 |
| PromotionId | Id della promozione | text | 50 |
| PromotionLineId | Id della riga promozione | text | 50 |
| [PromotionStatus](documentline.md#promotionstatus) | stato della promozione per quell'articolo | enum |  |
| RetailAmount | Totale documento Retail | dec |  |
| RetailAmountIncludingVat | Totale documento Retail incluso di IVA | dec |  |
| RetailDiscount1 | Sconto | dec |  |
| RetailDiscount2 | Sconto | dec |  |
| RetailDiscount3 | Sconto | dec |  |
| RetailDiscount4 | Sconto | dec |  |
| RetailDiscount5 | Sconto | dec |  |
| RetailDiscount6 | Sconto | dec |  |
| RetailDiscount7 | Sconto | dec |  |
| RetailFixedDiscount |  | dec |  |
| RetailNetUnitPrice | Prezzo unitario netto \(retail\) | dec |  |
| RetailPriceIncludesVat | Indica se il prezzo è ivato \(retail\) | bool |  |
| RetailPriceListId | Id listino \(retail\) | text | 50 |
| RetailUnitPrice | prezzo unitario \(retail\) | dec |  |
| SalesQty | Quantità totale espressa nell'unità di misura di vendita | dec |  |
| SalesUomId | Unità di misura di vendita | text | 10 |
| SaleTypeId | Id | text | 50 |
| [SaleTypeMode](documentline.md#saletypemode) | Modalità | enum |  |
| SeasonId | Id della stagione | text | 50 |
| ShipmentDescription | Descrizione spedizione | text | text |
| SourceReference | Numero del documento di riferimento | text | 50 |
| SourceReferenceType | Tipo della sorgente di riferimento | enum |  |
| SourceReferenceTypeId | Id del tipo della sorgente di riferimento | text | 50 |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| StartShipmentDate | Data inizio spedizione | date |  |
| SyncReference | Riferimento | text | 50 |
| Tag | Tag | text | 100 |
| TotalDiscount | Totale sconto | dec |  |
| UnitPrice | prezzo unitario | dec |  |
| UnitsPerPack | Unità per confezione | dec |  |
| UomLabel |  | text | 20 |
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

## AvailabilityMode

* 0: Regular
* 1: Virtual

## ChargeForUnpackaged

* 0: No
* 1: Yes

## LineStatus

* 0: Regular
* 1: ApprovalRequired

## LineType

* 0: Item
* 1: ManualItem
* 2: Note
* 3: ModelItem
* 4: VariableItem
* 5: Idrolab

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## PriceRecalculationStatus

* 0: None
* 1: ConfirmationRequired

## PromotionStatus

* 0: NotActive
* 1: ShouldChoosePromotion
* 2: PromoDaListinoPersonalizzato
* 3: Activated
* 4: AutomaticPromotionActivated
* 5: DirectPromotionActivated

## SaleTypeMode

* 0: Normal
* 1: TotalFreeSample
* 2: TaxableFreeSample
* 3: DiscountOnGoods
* 4: Promotion
