# ItemAvailability

<br><br> 

FilterMode 
---
Descrizione:  Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti <br> 
Tipo: Enum <br> 
Valore di default: 0 <br>
Valori:
<ul> 
<li>0 => Per magazzino dell'utente/agente</li>
<li>1 => Nessun filtro</li>
</ul><br>
GlobalAvailabilityMode 
---
Descrizione:  Modalità di calcolo della disponibilità globale <br> 
Tipo: Enum <br> 
Valore di default: 0 <br>
Valori:
<ul> 
<li>0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'</li>
<li>1 => Calcolata dalle disponibilità nei magazzini</li>
</ul><br>
QtyField 
---
Descrizione:  Campo da considerare per verificare la quantità disponibile <br> 
Tipo: Enum <br> 
Valore di default: 0 <br>
Valori:
<ul> 
<li>0 => SalesQty</li>
<li>1 => NumberOfPacks</li>
</ul><br>

