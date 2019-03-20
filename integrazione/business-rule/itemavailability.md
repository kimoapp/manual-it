# ItemAvailability

| Valore | Descrizione |
| :--- | :--- |
| [**FilterMode**](itemavailability.md#filtermode) | Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti |
| [**GlobalAvailabilityMode**](itemavailability.md#globalavailabilitymode) | Modalità di calcolo della disponibilità globale |
| [**QtyField**](itemavailability.md#qtyfield) | Campo da considerare per verificare la quantità disponibile |

## FilterMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Per magazzino dell'utente/agente
* 1 =&gt; Nessun filtro

## GlobalAvailabilityMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 =&gt; Calcolata dalle disponibilità nei magazzini

## QtyField

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; SalesQty
* 1 =&gt; NumberOfPacks

