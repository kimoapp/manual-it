---
description: Punti per la vendita di articoli
---

# PointsPerSale

**Chiavi**

* _Id_
* ItemEncodingType, ItemEncodingKey, AccountEncodingType, AccountEncodingKey, UomType, UomId, CurrencyId, StartDate, EndDate

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](pointspersale.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ItemEncodingKey | Chiave identificativa per gli articoli \(codice, gruppo, ...\) | text | 50 |
| [ItemEncodingType](pointspersale.md#itemencodingtype) | Tipo della chiave identificativa per gli articoli | enum |  |
| PointsPerFreeGiftSale | Punti per vendita 'in omaggio' | dec |  |
| PointsPerFreeGiftSaleRule | Regola per calcolare i punti per vendita 'in omaggio' | text | 100 |
| PointsPerPromotionSale | Punti per vendita 'in promozione' | dec |  |
| PointsPerPromotionSaleRule | Regola per calcolare i punti per vendita 'in promozione' | text | 100 |
| PointsPerRegularSale | Punti per vendita 'normale' | dec |  |
| PointsPerRegularSaleRule | Regola per calcolare i punti per vendita 'normale' | text | 100 |
| StartDate | Data inizio validità | date |  |
| UomId | Id dell'unità di misura \(di vendita o di imballo\) | text | 50 |
| [UomType](pointspersale.md#uomtype) | Tipo dell'unità di misura \(di vendita o di imballo\) | enum |  |

## AccountEncodingType

* 0: Account
* 4: PriceList
* 5: Composed

## ItemEncodingType

* 0: Item
* 5: ItemPromotionIdAndSaleType
* 6: ItemAndPromotionId

## UomType

* 0: Undefined
* 1: PackUom
* 2: SalesUom
.