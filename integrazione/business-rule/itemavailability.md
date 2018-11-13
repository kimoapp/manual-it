# ItemAvailability
FilterMode 
----
**Descrizione:** Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti	 
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Per magazzino dell'utente/agente
* 1 => Nessun filtro

GlobalAvailabilityMode 
----
**Descrizione:** Modalità di calcolo della disponibilità globale	 
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 => Calcolata dalle disponibilità nei magazzini

QtyField 
----
**Descrizione:** Campo da considerare per verificare la quantità disponibile	 
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => SalesQty
* 1 => NumberOfPacks

