---
description: Disponibilità 'offline' dei lotti
---

# ItemLotOfflineAvailability

**Chiavi**

* _Id_
* Lot, ItemId, WarehouseId, VariableItemId, StartAvailabilityDate

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AvailabilityAsFreeText | Campo testo libero in cui riportare la disponibilità strutturata come richiesto dal cliente | text | 50 |
| GlobalAvailability |  | dec |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| LastUpdateDate |  | dt |  |
| LogisticCenterAvailability |  | dec |  |
| Lot | Lotto | text | 50 |
| StartAvailabilityDate |  | date |  |
| UomId | Id dell'unità di misura in cui è espressa la disponibilità | text | 20 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| WarehouseAvailability |  | dec |  |
| WarehouseId | Id del magazzino a cui fa riferimento la disponibilità | text | 50 |
.