---
title: ItemAssociated
description:
keywords: schema, ItemAssociated
uid: kimo-integrator-schema/ItemAssociated
---

# ItemAssociated

<br>
**Chiavi**
- *Id*
- SourceItemId, AssociationType, AssociatedItemId, CustomerId, StartDate, EndDate
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| AssociatedItemId | Id dell'articolo associato | text | 50 |  |
| AssociationType | Tipo di associazione | enum |  | 1: Related, 2: Substitutive, 3: Alternative |
| CustomerId | Id del cliente | text | 50 |  |
| EndDate | Data fine validità | date |  |  |
| Id | Id | text | 50 |  |
| Priority |  | int |  |  |
| SourceItemId | Id dell'articolo di interesse | text | 50 |  |
| StartDate | Data inizio validità | date |  |  |

