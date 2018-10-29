---
title: PromotionLine
description:
keywords: schema, PromotionLine
uid: kimo-integrator-schema/PromotionLine
---

# PromotionLine

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| Description | Descrizione | text | text |  |
| Discount1 | Sconto | dec |  |  |
| Discount2 | Sconto | dec |  |  |
| Discount3 | Sconto | dec |  |  |
| EncodingKey | Chiave | text | 50 | I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione |
| EncodingType | Prefisso | text | 50 | I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata la promozione |
| EndDate | Data fine validità | date |  |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |  |
| GiftItemId | Indica il codice dell'articolo da dare in omaggio nelle promo N+M (se vuoto indica lo stesso articolo) | text | 50 |  |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |  |
| GiftQtyMode | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  | 0: NotIncluded, 1: Included |
| Id | Id | text | 50 |  |
| ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| Included |  | bool |  |  |
| LineNumber | Numero riga | int |  |  |
| Mandatory |  | bool |  |  |
| MaxDiscount | Sconto massimo | dec |  |  |
| MaxQty | Quantità massima | dec |  |  |
| MinQty | Quantità minima | dec |  |  |
| Notes | Note | text | text |  |
| PromotionId | Id della promozione | text | 50 |  |
| QtyDivisibilityRule | Indica se la quantità totale deve essere divisibile per l'unità per confezione | enum |  | 0: Default |
| QuantityRange1_Discount | Sconto | dec |  |  |
| QuantityRange1_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange1_Quantity | Quantità | dec |  |  |
| QuantityRange2_Discount | Sconto | dec |  |  |
| QuantityRange2_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange2_Quantity | Quantità | dec |  |  |
| QuantityRange3_Discount | Sconto | dec |  |  |
| QuantityRange3_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange3_Quantity | Quantità | dec |  |  |
| QuantityRange4_Discount | Sconto | dec |  |  |
| QuantityRange4_ImposedUnitPrice | Prezzo unitario imposto | dec |  |  |
| QuantityRange4_Quantity | Quantità | dec |  |  |
| SaleTypeId | Tipo vendita | text | 50 |  |
| StartDate | Data inizio validità | date |  |  |
| SuggestedQty | Quantità suggerita | dec |  |  |
| VatRateId | Id dell'aliquota IVA | text | 50 |  |

