# ErpDocument
AdvancedSearchFields 
----
**Descrizione:** Campi per la ricerca avanzata	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** ErpDocumentType	 
**Valori:**
* ErpDocumentType
* ErpLineFreeLookup
* ErpStatus
* Item
* SearchType

FilterPerUser 
----
**Descrizione:** Modalità di filtro dei documenti in base all'utente	 
**Tipo:** Enum	 
**Valore di default:** 1	 
**Valori:**
* 0 => Applica i filtri di default
* 1 => Filtra i documenti per 'proprietario' (owner)
* 2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate

ItemLiveSearch 
----
**Descrizione:** Abilita la ricerca 'live' degli articoli	 
**Tipo:** Boolean	 
**Valore di default:** True	 

KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Number&#124;AccountName	 
**Valori:**
* AccountName
* Number

