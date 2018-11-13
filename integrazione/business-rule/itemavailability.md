# ItemAvailability

<br><br> 

FilterMode 
----
**Descrizione:** Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti<br>
**Tipo:** Enum<br>
**Valore di default:** 0<br>
**Valori:**
* 0 => Per magazzino dell'utente/agente
* 1 => Nessun filtro

GlobalAvailabilityMode 
----
**Descrizione:** Modalità di calcolo della disponibilità globale<br>
**Tipo:** Enum<br>
**Valore di default:** 0<br>
**Valori:**
* 0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 => Calcolata dalle disponibilità nei magazzini

QtyField 
----
**Descrizione:** Campo da considerare per verificare la quantità disponibile<br>
**Tipo:** Enum<br>
**Valore di default:** 0<br>
**Valori:**
* 0 => SalesQty
* 1 => NumberOfPacks

