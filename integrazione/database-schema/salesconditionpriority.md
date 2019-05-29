---
description:>-
Priorità delle condizioni di vendita
---

# SalesConditionPriority

<br>
**Chiavi**
- *Id*
- SalesConditionTypeId, Type, SalesAgentId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| Id | Id | text | 50 |
| IsStandardSalesCondition | Indica se è una condizione standard | bool |  |
| Priority | Priorità | int |  |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesConditionTypeId | Id del tipo condizione di vendita | text | 1000 |
| ShouldIncludeStandardDiscountsInPrice | Indica se si richiede l'inclusione nel prezzo degli sconti standard | bool |  |
| Type |  | int |  |

