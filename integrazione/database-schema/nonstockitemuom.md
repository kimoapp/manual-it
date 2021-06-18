---
description: Unità di misura degli articoli non a stock
---

# NonStockItemUom

**Chiavi**

* _Id_
* ItemId, PackUomId, PackUnitUomId, SalesUomId, UnitsPerPack, Barcode

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Barcode | Codice a barre | text | 50 |
| [ChargeForUnpackaged](nonstockitemuom.md#chargeforunpackaged) | Addebita fuori confezione \(sfusi\) | enum |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| Label |  | text | 20 |
| ModelItemId | Id articolo modello | text | 50 |
| PackUnitUomId | Unità di misura unitaria d'imballo | text | 20 |
| PackUnitUomToSalesUomQtyRatio | Rapporto di conversione tra unità di misura unitaria d'imballo e unità di misura di vendita | dec |  |
| PackUomId | Unità di misura d'imballo | text | 20 |
| PricePerQtyMultiplier |  | dec |  |
| Priority | Priorità di utilizzo dell'unità di misura | int |  |
| SalesUomId | Unità di misura di vendita | text | 20 |
| UnitsPerPack | Unità per confezione | dec |  |
| [UnitsPerPackDivisibilityRule](nonstockitemuom.md#unitsperpackdivisibilityrule) | Indica se la quantità totale deve essere divisibile per l'unità per confezione | enum |  |

## ChargeForUnpackaged

* 0: No
* 1: Yes

## UnitsPerPackDivisibilityRule

* 0: AllowDivisibility
* 1: WarnIfDivided
* 2: DoNotAllowDivisibility

