# ItemAvailability

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| FilterMode | Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti | Enum | <ul>  <li>0 => Per magazzino dell'utente/agente</li> <li>1 => Nessun filtro</li></ul>| 0 |
| GlobalAvailabilityMode | Modalità di calcolo della disponibilità globale | Enum | <ul>  <li>0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'</li> <li>1 => Calcolata dalle disponibilità nei magazzini</li></ul>| 0 |
| QtyField | Campo da considerare per verificare la quantità disponibile | Enum | <ul>  <li>0 => SalesQty</li> <li>1 => NumberOfPacks</li></ul>| 0 |

