---
description: Costo articoli (netto, lordo, ...)
---
# ItemCost

<br>
**Chiavi**
- *Id*
- ItemId, StartDate, EndDate, CurrencyId, SalesUomId, UnitsPerPack
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| GrossCost | Costo lordo | dec |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| NetCost | Costo netto | dec |  |
| OtherCost | Altro costo | dec |  |
| SalesUomId | Id unità di misura di vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| [Type](#type) |  | enum |  |
| UnitsPerPack | Unità per confezione | dec |  |

Type
---
0: Regualar<br&gt;1: NetCost


