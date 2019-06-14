---
description: Promozioni
---

# Promotion

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| [ActivationMode](promotion.md#activationmode) | Modalità di attivazione | enum |  |
| AlternativePaymentId | Id del pagamento alternativo | text | 50 |
| [CustomerDiscountsRule](promotion.md#customerdiscountsrule) | Regola per lo sconto cliente | enum |  |
| Description | Descrizione | text | text |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| GiftFreeQty | Quantità in omaggio nelle promo N+M | dec |  |
| GiftPaidQty | Quantità di vendita nelle promo N+M | dec |  |
| [GiftQtyMode](promotion.md#giftqtymode) | Indica se la quantità in omaggio è da considerarsi compresa, nelle promo N+M | enum |  |
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
| [PricePrintingRule](promotion.md#priceprintingrule) | Regole di stampa | enum |  |
| [PromotionType](promotion.md#promotiontype) | Tipo promozione | enum |  |
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
## ActivationMode

0. Default
1. Automatic
## CustomerDiscountsRule

0. Default\_Or\_IncludeForCustomerGroupOnMichelangelo
1. IncludeForCustomer
2. IncludeForGrossCost
3. PreserveDiscountsOnImposedUnitPrice
4. TakeGrossUnitPrice
5. TakeNetUnitPrice
## GiftQtyMode

0. Quantità gratuita 'inclusa' in quella a pagamento
1. Quantità gratuita NON 'inclusa' in quella a pagamento
## PricePrintingRule

0. Print
1. NoPrint
## PromotionType

0. Classic
1. Kit
2. NPlusM
3. NPlusM\_MonoReference

