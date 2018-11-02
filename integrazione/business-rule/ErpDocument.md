# ErpDocument

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| AdvancedSearchFields | Campi per la ricerca avanzata | Valori separati da pipe | <ul>  <li>ErpDocumentType</li> <li>ErpLineFreeLookup</li> <li>ErpStatus</li> <li>Item</li> <li>SearchType</li></ul>| ErpDocumentType |
| FilterPerUser | Modalità di filtro dei documenti in base all'utente | Enum | <ul>  <li>0 => Applica i filtri di default</li> <li>1 => Filtra i documenti per 'proprietario' (owner)</li> <li>2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate</li></ul>| 1 |
| ItemLiveSearch | Abilita la ricerca 'live' degli articoli | Boolean | <ul> </ul>| True |
| KeywordSearchFields | Campi per la ricerca testuale | Valori separati da pipe | <ul>  <li>AccountName</li> <li>Number</li></ul>| Number&#124;AccountName |

