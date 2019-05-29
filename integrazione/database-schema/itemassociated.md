# ItemAssociated

Articoli alternativi, sostitutivi o collegati

<br>
**Chiavi**
- *Id*
- SourceItemId, AssociationType, AssociatedItemId, CustomerId, StartDate, EndDate
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| AssociatedItemId | Id dell'articolo associato | text | 50 |
| [AssociationType](#associationtype) | Tipo di associazione | enum |  |
| CustomerId | Id del cliente | text | 50 |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| Priority |  | int |  |
| SourceItemId | Id dell'articolo di interesse | text | 50 |
| StartDate | Data inizio validità | date |  |

AssociationType
---
1: Related<br>2: Substitutive<br>3: Alternative

