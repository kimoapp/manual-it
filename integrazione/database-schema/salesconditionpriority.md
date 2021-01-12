---
description: Priorità delle condizioni di vendita
---

# SalesConditionPriority

**Chiavi**

* _Id_
* SalesConditionTypeId, Type, SalesAgentId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| ApplyCondition | Indica la condizione per cui applicare la condizione di vendita \(es. solo se migliorativa\) | int |  |
| DiscountColumn | Se è stato trovato uno sconto, indica la colonna su cui applicare gli sconti | int |  |
| DiscountNextSalesCondition | Se è stato trovato uno sconto, indica la prossima condizione di vendita da ricercare | text | 50 |
| DiscountStop | Se è stato trovato uno sconto, indica se fermarsi nella ricerca delle condizioni di vendita | int |  |
| Id | Id | text | 50 |
| ImposedPriceNextSalesCondition | Se è stato trovato un prezzo imposto, indica la prossima condizione di vendita da ricercare | text | 50 |
| ImposedPriceStop | Se è stato trovato un prezzo imposto, indica se fermarsi nella ricerca delle condizioni di vendita | int |  |
| IsStandardSalesCondition | Indica se è una condizione standard | bool |  |
| Priority | Priorità | int |  |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesConditionTypeId | Id del tipo condizione di vendita | text | 1000 |
| ShouldIncludeStandardDiscountsInPrice | Indica se si richiede l'inclusione nel prezzo degli sconti standard | bool |  |
| Type |  | int |  |

