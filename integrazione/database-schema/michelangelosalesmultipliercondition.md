---
description: Condizioni di ricarico nell'Erp Michelangelo
---

# MichelangeloSalesMultiplierCondition

**Chiavi**

* _Id_
* ItemId, SalesUomId, UnitsPerPack, CurrencyId, StartDate, EndDate, SalesAgentId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| CurrencyId | Id della valuta | text | 50 |
| DiscardOnNetCost | Condizione di ricarico da scartare se costo è netto | bool |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ImposedUnitPrice | Prezzo unitario imposto | dec |  |
| ItemId | Id dell'articolo | text | 50 |
| Multiplier | Ricarico | dec |  |
| ReferenceCostTypeId | Id del costo di riferimento | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesDiscountCategoryId | Id della categoria sconto vendita | text | 2 |
| SalesUomId | Id unità di misura di vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| Status | Stato | text | 1 |
| UnitsPerPack | Unità per confezione | dec |  |
| UseMultiplier | Indica se usare il ricarico | bool |  |
.