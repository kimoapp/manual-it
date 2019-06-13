# ItemAvailability

| Valore| Descrizione |
| :--- | :--- |
| [**FilterMode**](itemavailability.md#filtermode) | Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti |
| [**GlobalAvailabilityMode**](itemavailability.md#globalavailabilitymode) | Modalità di calcolo della disponibilità globale |
| [**QtyField**](itemavailability.md#qtyfield) | Campo da considerare per verificare la quantità disponibile |

-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**

* 0 => Per magazzino dell'utente/agente
* 1 => Nessun filtro

-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**

* 0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 => Calcolata dalle disponibilità nei magazzini

-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**

* 0 => SalesQty
* 1 => NumberOfPacks

