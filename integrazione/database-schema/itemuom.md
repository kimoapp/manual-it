---
description: Unità di misura degli articoli
---
# ItemUom

<br>
**Chiavi**
- *Id*
- ItemId, PackUomId, PackUnitUomId, SalesUomId, UnitsPerPack, Barcode
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| Barcode | Codice a barre | text | 50 |
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
| [UnitsPerPackDivisibilityRule](#unitsperpackdivisibilityrule) | Indica se la quantità totale deve essere divisibile per l'unità per confezione | enum |  |

UnitsPerPackDivisibilityRule
---
0: AllowDivisibility<br&gt;1: WarnIfDivided<br&gt;2: DoNotAllowDivisibility


