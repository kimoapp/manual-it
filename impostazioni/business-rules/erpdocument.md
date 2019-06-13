# ErpDocument

| Valore| Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](#advancedsearchfields)** | Campi per la ricerca avanzata |
| [**FilterPerUser**](#filterperuser)** | Modalità di filtro dei documenti in base all'utente |
| [**ItemLiveSearch**](#itemlivesearch)** | Abilita la ricerca 'live' degli articoli |
| [**KeywordSearchFields**](#keywordsearchfields)** | Campi per la ricerca testuale |

$h2 AdvancedSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** ErpDocumentType	 
**Valori:**
* ErpDocumentType
* ErpLineFreeLookup
* ErpStatus
* Item
* SearchType

$h2 FilterPerUser 
-----
**Tipo:** Enum	 
**Valore di default:** 1	 
**Valori:**
* 0 => Applica i filtri di default
* 1 => Filtra i documenti per 'proprietario' (owner)
* 2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando comunque le testate

$h2 ItemLiveSearch 
-----
**Tipo:** Boolean	 
**Valore di default:** True	 

$h2 KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Number&#124;AccountName&#124;AccountName2	 
**Valori:**
* AccountName
* Number

