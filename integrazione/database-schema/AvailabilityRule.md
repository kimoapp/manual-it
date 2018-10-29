---
title: AvailabilityRule
description:
keywords: schema, AvailabilityRule
uid: kimo-integrator-schema/AvailabilityRule
---

# AvailabilityRule

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| Description | Descrizione | text | 100 |  |
| Id | Id | text | 50 |  |
| ItemAvailabilityValidationRule | Indica se la quantità inserita deve essere confrontata con la disponibilità dell'articolo | enum |  | 0: DoNotValidate, 1: BlockIfExceed |
| ShouldShowItemAvailability | Indica se la disponibilità dell'articolo è visibile in fase di inserimento quantità | bool |  |  |

