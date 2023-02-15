---
description: Righe dei riassortimenti
---

# ReassortmentLine

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| [ActiveStatus](reassortmentline.md#activestatus) |  | enum |  |
| Availability | Disponibilità | dec |  |
| AverageDiscount | Sconto | dec |  |
| AverageNetUnitPrice | Prezzo netto medio | dec |  |
| AverageUnitPrice | Prezzo unitario | dec |  |
| CurrencyId | Id della valuta | text | 50 |
| CurrentDiscount1 | Sconto | dec |  |
| CurrentDiscount2 | Sconto | dec |  |
| CurrentDiscount3 | Sconto | dec |  |
| CurrentDiscount4 | Sconto | dec |  |
| CurrentDiscount5 | Sconto | dec |  |
| CurrentDiscount6 | Sconto | dec |  |
| CurrentDiscount7 | Sconto | dec |  |
| CurrentInPromotion | In promozione | bool |  |
| CurrentNetUnitPrice | Prezzo unitario netto | dec |  |
| CurrentSaleTypeId | Tipo vendita | text | 50 |
| CurrentUnitPrice | Prezzo unitario | dec |  |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeQty1\_NumberOfPurchases | Numero ordini | int |  |
| FreeQty1\_SalesQty | Quantità di vendita | dec |  |
| FreeQty2\_NumberOfPurchases | Numero ordini | int |  |
| FreeQty2\_SalesQty | Quantità di vendita | dec |  |
| FreeQty3\_NumberOfPurchases | Numero ordini | int |  |
| FreeQty3\_SalesQty | Quantità di vendita | dec |  |
| FreeQty4\_NumberOfPurchases | Numero ordini | int |  |
| FreeQty4\_SalesQty | Quantità di vendita | dec |  |
| FreeQty5\_NumberOfPurchases | Numero ordini | int |  |
| FreeQty5\_SalesQty | Quantità di vendita | dec |  |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id della riga del riassortimento | text | 50 |
| ItemDescription | Descrizione articolo | text | 130 |
| ItemId | Id articolo | text | 50 |
| LastSaleDate | Data ultima vendita | date |  |
| LastSaleDiscount1 | Sconto | dec |  |
| LastSaleDiscount2 | Sconto | dec |  |
| LastSaleDiscount3 | Sconto | dec |  |
| LastSaleDiscount4 | Sconto | dec |  |
| LastSaleDiscount5 | Sconto | dec |  |
| LastSaleDiscount6 | Sconto | dec |  |
| LastSaleDiscount7 | Sconto | dec |  |
| LastSaleInPromotion | Flag indicante se l'ultima vendita era in promozione | bool |  |
| LastSaleNetUnitPrice | Prezzo unitario netto | dec |  |
| LastSaleNumberOfPacks | Numero confezioni ultima vendita | dec |  |
| LastSalePackUnitQty | Quantità ultima vendita espressa nell'unità di misura unitaria di imballo | dec |  |
| LastSaleSalesQty | Quantità ultima vendita espressa nell'unità di misura di vendita | dec |  |
| LastSaleSaleTypeId | Tipo vendita dell'ultima vendita | text | 50 |
| LastSaleUnitPrice | Prezzo unitario | dec |  |
| LineNumber | Numero riga | int |  |
| [LineType](reassortmentline.md#linetype) | Tipo riga | enum |  |
| [LockedFields](reassortmentline.md#lockedfields) | Campi bloccati per l'editing nei documenti | enum |  |
| ManufacturerId | Id del produttore | text | 50 |
| ManufacturerItemId | Id dell'articolo produttore | text | 50 |
| Notes | Note | text | text |
| PackUnitUomId | Id dell'unità di misura unitaria di imballo | text | 20 |
| PackUomId | Id dell'unità di misura di imballo | text | 20 |
| ReassortmentId | Id del riassortimento | text | 50 |
| SalesUomId | Id dell'unità di misura di vendita | text | 20 |
| SeasonId | Id della stagione | text | 50 |
| TotalAmount | Importo totale | dec |  |
| TotalNumberOfPacks | Numero confezioni totale | dec |  |
| TotalNumberOfPurchases | Numero di acquisti totale | dec |  |
| TotalOutstandingQty | Quantità totale rimanente | dec |  |
| TotalPackUnitQty | Quantità totale espressa nell'unità di misura unitaria di imballo | dec |  |
| TotalSalesQty | Quantità totale espressa nell'unità di misura di vendita | dec |  |
| TotalShippedQty | Quantità totale consegnata | dec |  |
| TrademarkId | Id del marchio | text | 50 |
| UnitsPerPack | Quantità per confezione | dec |  |
| VariableId1 | Id della variante | text | 50 |
| VariableId2 | Id della variante | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |

## ActiveStatus

* 0: Active
* 1: Deactivated

## LineType

* 0: Item
* 1: ManualItem
* 2: Note
* 3: ModelItem
* 4: VariableItem
* 5: Idrolab

## LockedFields

* 0: None
* 1: UnitPrice
* 2: Discounts
* 4: SaleType
* 8: PriceList
* 16: QuantitiesAndUom
* 32: Delete
* 64: LineDuplication
.