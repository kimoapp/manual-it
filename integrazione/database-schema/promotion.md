# Promotion
Promozioni

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| [ActivationMode](#activationmode) | Modalità di attivazione | enum |  |
| AlternativePaymentId | Id del pagamento alternativo | text | 50 |
| [CustomerDiscountsRule](#customerdiscountsrule) | Regola per lo sconto cliente | enum |  |
| Description | Descrizione | text | text |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |
| [GiftQtyMode](#giftqtymode) | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  |
| Id | Id | text | 50 |
| KitPrice |  | dec |  |
| KitQuantity |  | dec |  |
| MaxGiftAmount |  | dec |  |
| MinAmount | Importo minimo | dec |  |
| MinItems | Numero minimo di articoli | int |  |
| MinQty | Quantità minima | dec |  |
| Notes | Note | text | text |
| Number | Numero promozione | text | 50 |
| PackUomId |  | text | 20 |
| [PricePrintingRule](#priceprintingrule) | Regole di stampa | enum |  |
| [PromotionType](#promotiontype) | Tipo promozione | enum |  |
| QuantityRange1_Discount | Sconto | dec |  |
| QuantityRange1_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange1_Quantity | Quantità | dec |  |
| QuantityRange2_Discount | Sconto | dec |  |
| QuantityRange2_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange2_Quantity | Quantità | dec |  |
| QuantityRange3_Discount | Sconto | dec |  |
| QuantityRange3_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange3_Quantity | Quantità | dec |  |
| QuantityRange4_Discount | Sconto | dec |  |
| QuantityRange4_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange4_Quantity | Quantità | dec |  |
| SaleTypeId | Tipo vendita | text | 50 |
| StartDate | Data inizio validità | date |  |

ActivationMode
---
0: Default<br>1: Automatic
CustomerDiscountsRule
---
0: Default_Or_IncludeForCustomerGroupOnMichelangelo<br>1: IncludeForCustomer<br>2: IncludeForGrossCost<br>3: PreserveDiscountsOnImposedUnitPrice<br>4: TakeGrossUnitPrice<br>5: TakeNetUnitPrice
GiftQtyMode
---
0: Quantità gratuita 'inclusa' in quella a pagamento<br>1: Quantità gratuita NON 'inclusa' in quella a pagamento
PricePrintingRule
---
0: Print<br>1: NoPrint
PromotionType
---
0: Classic<br>1: Kit<br>2: NPlusM<br>3: NPlusM_MonoReference

