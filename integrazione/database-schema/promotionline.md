---
description: Righe promozioni
---

# PromotionLine

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| [ActivationMode](promotionline.md#activationmode) | Modalità di attivazione | enum |  |
| Description | Descrizione | text | text |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| DiscountColumn | Colonna su cui applicare gli sconti | int |  |
| DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| [EncodingKey](promotionline.md#encodingkey) | Chiave | text | 50 |
| [EncodingType](promotionline.md#encodingtype) | Prefisso | text | 50 |
| EndDate | Data fine validità | date |  |
| FixedDiscount | Sconto importo | dec |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |
| GiftItemId | Indica il codice dell'articolo da dare in omaggio nelle promo N+M \(se vuoto indica lo stesso articolo\) | text | 50 |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |
| [GiftQtyMode](promotionline.md#giftqtymode) | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  |
| Id | Id | text | 50 |
| ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| Included |  | bool |  |
| LineNumber | Numero riga | int |  |
| Mandatory |  | bool |  |
| MaxDiscount | Sconto massimo | dec |  |
| MaxGiftAmount | Importo massimo omaggiabile | dec |  |
| MaxQty | Quantità massima | dec |  |
| MinGiftAmount | Importo minimo omaggiabile | dec |  |
| MinQty | Quantità minima | dec |  |
| [MultipleQty](promotionline.md#multipleqty) | Quantità multipla | dec |  |
| NextSalesCondition | Prossima condizione di vendita da ricercare | text | 50 |
| Notes | Note | text | text |
| PromotionId | Id della promozione | text | 50 |
| [QtyDivisibilityRule](promotionline.md#qtydivisibilityrule) | Indica se la quantità totale deve essere divisibile per l'unità per confezione | enum |  |
| QuantityRange1\_Discount | Sconto | dec |  |
| QuantityRange1\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange1\_Quantity | Quantità | dec |  |
| QuantityRange2\_Discount | Sconto | dec |  |
| QuantityRange2\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange2\_Quantity | Quantità | dec |  |
| QuantityRange3\_Discount | Sconto | dec |  |
| QuantityRange3\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange3\_Quantity | Quantità | dec |  |
| QuantityRange4\_Discount | Sconto | dec |  |
| QuantityRange4\_ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| QuantityRange4\_Quantity | Quantità | dec |  |
| SaleTypeId | Tipo vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| Stop | Indica se fermarsi nella ricerca delle condizioni di vendita | int |  |
| SuggestedQty | Quantità suggerita | dec |  |
| VatRateId | Id dell'aliquota IVA | text | 50 |

## ActivationMode

* 0: Default
* 1: Automatic

## EncodingKey

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione

## EncodingType

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione

## GiftQtyMode

* 0: Quantità gratuita 'inclusa' in quella a pagamento
* 1: Quantità gratuita NON 'inclusa' in quella a pagamento

## MultipleQty

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## QtyDivisibilityRule

* 0: Default
