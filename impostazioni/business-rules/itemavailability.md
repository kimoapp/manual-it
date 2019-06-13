# ItemAvailability
| Valore| Descrizione |
| --- | --- |
| **[FilterMode](#filtermode)** | Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti |
| **[GlobalAvailabilityMode](#globalavailabilitymode)** | Modalità di calcolo della disponibilità globale |
| **[QtyField](#qtyfield)** | Campo da considerare per verificare la quantità disponibile |

FilterMode 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Per magazzino dell'utente/agente
* 1 => Nessun filtro

GlobalAvailabilityMode 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 => Calcolata dalle disponibilità nei magazzini

QtyField 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => SalesQty
* 1 => NumberOfPacks

