---
description: Articoli alternativi, sostitutivi o collegati
---

# ItemAssociated

**Chiavi**

* _Id_
* SourceItemId, AssociationType, AssociatedItemId, CustomerId, StartDate, EndDate, SourceItemGroupLevel1Id, SourceItemGroupLevel2Id, SourceItemGroupLevel3Id, SourceItemGroupLevel4Id, SourceManufactuerId, SourceTrademarkId, SourceCollectionId, SourceItemSeriesId, SourceLineId, SourceItemClassificationId, SourceGenderId, SourceSeasonId, AssociatedItemGroupLevel1Id, AssociatedItemGroupLevel2Id, AssociatedItemGroupLevel3Id, AssociatedItemGroupLevel4Id, AssociatedManufactuerId, AssociatedTrademarkId, AssociatedCollectionId, AssociatedItemSeriesId, AssociatedLineId, AssociatedItemClassificationId, AssociatedGenderId, AssociatedSeasonId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AssociatedCollectionId |  | text | 50 |
| AssociatedGenderId |  | text | 50 |
| AssociatedItemClassificationId |  | text | 100 |
| AssociatedItemGroupLevel1Id |  | text | 50 |
| AssociatedItemGroupLevel2Id |  | text | 50 |
| AssociatedItemGroupLevel3Id |  | text | 50 |
| AssociatedItemGroupLevel4Id |  | text | 50 |
| AssociatedItemId | Id dell'articolo associato | text | 50 |
| AssociatedItemSeriesId |  | text | 50 |
| AssociatedLineId |  | text | 50 |
| AssociatedManufactuerId |  | text | 50 |
| AssociatedSeasonId |  | text | 50 |
| AssociatedTrademarkId |  | text | 50 |
| [AssociationType](itemassociated.md#associationtype) | Tipo di associazione | enum |  |
| CustomerId | Id del cliente | text | 50 |
| Description |  | text | 100 |
| EndDate | Data fine validità | date |  |
| FilePath |  | text | 100 |
| Id | Id | text | 50 |
| Priority |  | int |  |
| SalesQty |  | dec |  |
| SalesUomId |  | text | 50 |
| SourceCollectionId |  | text | 50 |
| SourceGenderId |  | text | 50 |
| SourceItemClassificationId |  | text | 100 |
| SourceItemGroupLevel1Id |  | text | 50 |
| SourceItemGroupLevel2Id |  | text | 50 |
| SourceItemGroupLevel3Id |  | text | 50 |
| SourceItemGroupLevel4Id |  | text | 50 |
| SourceItemId | Id dell'articolo di interesse | text | 50 |
| SourceItemSeriesId |  | text | 50 |
| SourceLineId |  | text | 50 |
| SourceManufactuerId |  | text | 50 |
| SourceSeasonId |  | text | 50 |
| SourceTrademarkId |  | text | 50 |
| StartDate | Data inizio validità | date |  |

## AssociationType

* 1: Related
* 2: Substitutive
* 3: Alternative
* 4: Grouped
* 5: Kit
