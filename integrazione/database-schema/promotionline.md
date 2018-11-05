# PromotionLine

  
 **Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Description | Descrizione | text | text |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| [EncodingKey](promotionline.md#EncodingKey) | Chiave | text | 50 |
| [EncodingType](promotionline.md#EncodingType) | Prefisso | text | 50 |
| EndDate | Data fine validità | date |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |
| GiftItemId | Indica il codice dell'articolo da dare in omaggio nelle promo N+M \(se vuoto indica lo stesso articolo\) | text | 50 |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |
| [GiftQtyMode](promotionline.md#GiftQtyMode) | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  |
| Id | Id | text | 50 |
| ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| Included |  | bool |  |
| LineNumber | Numero riga | int |  |
| Mandatory |  | bool |  |
| MaxDiscount | Sconto massimo | dec |  |
| MaxQty | Quantità massima | dec |  |
| MinQty | Quantità minima | dec |  |
| Notes | Note | text | text |
| PromotionId | Id della promozione | text | 50 |
| [QtyDivisibilityRule](promotionline.md#QtyDivisibilityRule) | Indica se la quantità totale deve essere divisibile per l'unità per confezione | enum |  |
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
| SuggestedQty | Quantità suggerita | dec |  |
| VatRateId | Id dell'aliquota IVA | text | 50 |

## EncodingKey

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione

## EncodingType

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione

## GiftQtyMode

0: NotIncluded 1: Included

## QtyDivisibilityRule

0: Default

