# Fulfillment

| Valore | Descrizione |
| :--- | :--- |
| [**AvailabilitiesToInclude**](fulfillment.md#availabilitiestoinclude) | Disponibilità da considerare nel calcolo delle date di evadibilità |
| [**ContactUsVisibilityMode**](fulfillment.md#contactusvisibilitymode) | Visibilità della funzione 'Contattaci' |
| [**DateVisibilityMode**](fulfillment.md#datevisibilitymode) | Visibilità della funzione  |
| [**FulfillableForShipmentOnRequestedDateValidationMode**](fulfillment.md#fulfillableforshipmentonrequesteddatevalidationmode) | Modalità di validazione dell'evadibilità rispetto alla data richiesta consegna |

## AvailabilitiesToInclude

**Tipo:** Valori separati da pipe  
**Valore di default:** 1\|2\|3  
**Valori:**

* 0 =&gt; Undefined
* 1 =&gt; Warehouse
* 2 =&gt; LogisticCenter
* 3 =&gt; Global

## ContactUsVisibilityMode

**Tipo:** Enum  
**Valore di default:** 1  
**Valori:**

* 0 =&gt; Hide
* 1 =&gt; Show

## DateVisibilityMode

**Tipo:** Enum  
**Valore di default:** 1  
**Valori:**

* 0 =&gt; Hide
* 1 =&gt; Show

## FulfillableForShipmentOnRequestedDateValidationMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Error
* 1 =&gt; Warning
