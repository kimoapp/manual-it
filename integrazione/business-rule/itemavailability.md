# ItemAvailability

<br><br> 

FilterMode 
---
<br> Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti <br> 
Enum <br> 
0 <br>
<ul> 
<li>0 => Per magazzino dell'utente/agente</li>
<li>1 => Nessun filtro</li>
</ul>
GlobalAvailabilityMode 
---
<br> Modalità di calcolo della disponibilità globale <br> 
Enum <br> 
0 <br>
<ul> 
<li>0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'</li>
<li>1 => Calcolata dalle disponibilità nei magazzini</li>
</ul>
QtyField 
---
<br> Campo da considerare per verificare la quantità disponibile <br> 
Enum <br> 
0 <br>
<ul> 
<li>0 => SalesQty</li>
<li>1 => NumberOfPacks</li>
</ul>

