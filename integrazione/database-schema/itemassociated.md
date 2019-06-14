---
description: Articoli alternativi, sostitutivi o collegati
---

# ItemAssociated

**Chiavi**

* _Id_
* SourceItemId, AssociationType, AssociatedItemId, CustomerId, StartDate, EndDate

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AssociatedItemId | Id dell'articolo associato | text | 50 |
| [AssociationType](itemassociated.md#associationtype) | Tipo di associazione | enum |  |
| CustomerId | Id del cliente | text | 50 |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| Priority |  | int |  |
| SourceItemId | Id dell'articolo di interesse | text | 50 |
| StartDate | Data inizio validità | date |  |
## AssociationType

* 1: Related
* 2: Substitutive
* 3: Alternative

