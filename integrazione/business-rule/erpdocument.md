# ErpDocument

<br><br> 

AdvancedSearchFields 
---
Descrizione:  Campi per la ricerca avanzata <br> 
Tipo: Valori separati da pipe <br> 
Valore di default: ErpDocumentType <br>
Valori:
<ul> 
<li>ErpDocumentType</li>
<li>ErpLineFreeLookup</li>
<li>ErpStatus</li>
<li>Item</li>
<li>SearchType</li>
</ul><br>
FilterPerUser 
---
Descrizione:  Modalità di filtro dei documenti in base all'utente <br> 
Tipo: Enum <br> 
Valore di default: 1 <br>
Valori:
<ul> 
<li>0 => Applica i filtri di default</li>
<li>1 => Filtra i documenti per 'proprietario' (owner)</li>
<li>2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate</li>
</ul><br>
ItemLiveSearch 
---
Descrizione:  Abilita la ricerca 'live' degli articoli <br> 
Tipo: Boolean <br> 
Valore di default: True <br>
Valori:
<ul> 
</ul><br>
KeywordSearchFields 
---
Descrizione:  Campi per la ricerca testuale <br> 
Tipo: Valori separati da pipe <br> 
Valore di default: Number&#124;AccountName <br>
Valori:
<ul> 
<li>AccountName</li>
<li>Number</li>
</ul><br>

