# ErpDocument

<br><br> 

AdvancedSearchFields 
----
**Descrizione:** Campi per la ricerca avanzata<br>
**Tipo:** Valori separati da pipe<br>
**Valore di default:** ErpDocumentType<br>
**Valori:**
* ErpDocumentType
* ErpLineFreeLookup
* ErpStatus
* Item
* SearchType

FilterPerUser 
----
**Descrizione:** Modalità di filtro dei documenti in base all'utente<br>
**Tipo:** Enum<br>
**Valore di default:** 1<br>
**Valori:**
* 0 => Applica i filtri di default
* 1 => Filtra i documenti per 'proprietario' (owner)
* 2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate

ItemLiveSearch 
----
**Descrizione:** Abilita la ricerca 'live' degli articoli<br>
**Tipo:** Boolean<br>
**Valore di default:** True<br>
**Valori:**

KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale<br>
**Tipo:** Valori separati da pipe<br>
**Valore di default:** Number&#124;AccountName<br>
**Valori:**
* AccountName
* Number

