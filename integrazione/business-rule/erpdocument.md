# ErpDocument
[AdvancedSearchFields](#advancedsearchfields)	 
**Descrizione:** Campi per la ricerca avanzata	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** ErpDocumentType	 
[FilterPerUser](#filterperuser)	 
**Descrizione:** Modalità di filtro dei documenti in base all'utente	 
**Tipo:** Enum	 
**Valore di default:** 1	 
[ItemLiveSearch](#itemlivesearch)	 
**Descrizione:** Abilita la ricerca 'live' degli articoli	 
**Tipo:** Boolean	 
**Valore di default:** True	 
[KeywordSearchFields](#keywordsearchfields)	 
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Number&#124;AccountName	 
AdvancedSearchFields 
-----

**Valori:**
* ErpDocumentType
* ErpLineFreeLookup
* ErpStatus
* Item
* SearchType

FilterPerUser 
-----

**Valori:**
* 0 => Applica i filtri di default
* 1 => Filtra i documenti per 'proprietario' (owner)
* 2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate



KeywordSearchFields 
-----

**Valori:**
* AccountName
* Number

