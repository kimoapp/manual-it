# Promotion

| Valore | Descrizione |
| :--- | :--- |
| [**ActivationFrequency**](promotion.md#activationfrequency) | Indica se è possibile attivare più volte la stessa promozione all'interno di un documento |
| [**ActivationWorkflow**](promotion.md#activationworkflow) | Modalità di attivazione delle promozioni |
| [**PriceDiscountsRuleForGiftLine**](promotion.md#pricediscountsruleforgiftline) | Regola di calcolo del prezzo per le righe con articoli in omaggio |
| [**SaleTypeIdForGiftItems**](promotion.md#saletypeidforgiftitems) | Id interno del tipo vendita da usare per gli articoli in omaggio nelle promozioni di tipo N+M |
| [**SortFields**](promotion.md#sortfields) | Campi per l'ordinamento |
| [**VisibleLineDiscounts**](promotion.md#visiblelinediscounts) | Numero di sconti visibili nell'editor delle promozioni |

## ActivationFrequency

**Tipo:** Enum  
**Valori:**

* 0 =&gt; OneActivationPerDocument
* 1 =&gt; MoreActivationsPerDocument

## ActivationWorkflow

**Tipo:** Enum  
**Valori:**

* 0 =&gt; ShowDetailsAndRequireConfirmation
* 1 =&gt; QuickActivation

## PriceDiscountsRuleForGiftLine

**Tipo:** Nullable`1

## SaleTypeIdForGiftItems

**Tipo:** String

## SortFields

**Tipo:** Valori separati da pipe  
**Valori:**

* Description
* Id
* Notes
* Number

## VisibleLineDiscounts

**Tipo:** Valori separati da pipe
