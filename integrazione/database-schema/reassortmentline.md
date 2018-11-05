# ReassortmentLine

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| [ActiveStatus](#ActiveStatus) |  | enum |  |
| Availability | Disponibilità | dec |  |
| AverageDiscount | Sconto | dec |  |
| AverageUnitPrice | Prezzo unitario | dec |  |
| CurrencyId | Id della valuta | text | 50 |
| CurrentDiscount1 | Sconto | dec |  |
| CurrentDiscount2 | Sconto | dec |  |
| CurrentDiscount3 | Sconto | dec |  |
| CurrentDiscount4 | Sconto | dec |  |
| CurrentDiscount5 | Sconto | dec |  |
| CurrentInPromotion | In promozione | bool |  |
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
| FreeQty1_NumberOfPurchases | Numero ordini | int |  |
| FreeQty1_SalesQty | Quantità di vendita | dec |  |
| FreeQty2_NumberOfPurchases | Numero ordini | int |  |
| FreeQty2_SalesQty | Quantità di vendita | dec |  |
| FreeQty3_NumberOfPurchases | Numero ordini | int |  |
| FreeQty3_SalesQty | Quantità di vendita | dec |  |
| FreeQty4_NumberOfPurchases | Numero ordini | int |  |
| FreeQty4_SalesQty | Quantità di vendita | dec |  |
| FreeQty5_NumberOfPurchases | Numero ordini | int |  |
| FreeQty5_SalesQty | Quantità di vendita | dec |  |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id della riga del riassortimento | text | 50 |
| ItemDescription | Descrizione articolo | text | 130 |
| ItemId | Id articolo | text | 50 |
| LastSaleDate | Data | date |  |
| LastSaleDiscount1 | Sconto | dec |  |
| LastSaleDiscount2 | Sconto | dec |  |
| LastSaleDiscount3 | Sconto | dec |  |
| LastSaleDiscount4 | Sconto | dec |  |
| LastSaleDiscount5 | Sconto | dec |  |
| LastSaleInPromotion | In promozione | bool |  |
| LastSaleNumberOfPacks | Numero confezioni | dec |  |
| LastSalePackUnitQty | Quantità totale espressa nell'unità di misura unitaria di imballo | dec |  |
| LastSaleSalesQty | Quantità totale espressa nell'unità di misura di vendita | dec |  |
| LastSaleSaleTypeId | Tipo vendita | text | 50 |
| LastSaleUnitPrice | Prezzo unitario | dec |  |
| LineNumber | Numero riga | int |  |
| [LineType](#LineType) | Tipo riga | enum |  |
| [LockedFields](#LockedFields) | Campi bloccati per l'editing nei documenti | enum |  |
| Notes | Note | text | text |
| PackUnitUomId | Id dell'unità di misura unitaria di imballo | text | 20 |
| PackUomId | Id dell'unità di misura di imballo | text | 20 |
| ReassortmentId | Id del riassortimento | text | 50 |
| SalesUomId | Id dell'unità di misura di vendita | text | 20 |
| SeasonId | Id della stagione | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| UnitsPerPack | Quantità per confezione | dec |  |
| VariableId1 | Id della variante | text | 50 |
| VariableId2 | Id della variante | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |

A ActiveStatus
---
0: Active
1: Deactivated
A LineType
---
0: Item
1: ManualItem
2: Note
3: ModelItem
4: VariableItem
5: Idrolab
A LockedFields
---
0: None
1: UnitPrice
2: Discounts
4: SaleType

