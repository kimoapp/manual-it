# ItemAvailability
[FilterMode](#filtermode)	 
----
**Descrizione:** Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti	 
**Tipo:** Enum	 
**Valore di default:** 0	 
[GlobalAvailabilityMode](#globalavailabilitymode)	 
----
**Descrizione:** Modalità di calcolo della disponibilità globale	 
**Tipo:** Enum	 
**Valore di default:** 0	 
[QtyField](#qtyfield)	 
----
**Descrizione:** Campo da considerare per verificare la quantità disponibile	 
**Tipo:** Enum	 
**Valore di default:** 0	 
FilterMode 
-----

**Valori:**
* 0 => Per magazzino dell'utente/agente
* 1 => Nessun filtro

GlobalAvailabilityMode 
-----

**Valori:**
* 0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 => Calcolata dalle disponibilità nei magazzini

QtyField 
-----

**Valori:**
* 0 => SalesQty
* 1 => NumberOfPacks

