# Item
[AdvancedSearchFields](#advancedsearchfields)	 
----
**Descrizione:** Campi per la ricerca avanzata	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** ItemGroupLevel1&#124;ItemGroupLevel2	 
[IdEncodingType](#idencodingtype)	 
----
**Descrizione:** Modalità di codifica dei codici articoli	 
**Tipo:** Enum	 
**Valore di default:** 0	 
[ItemFormUrlTemplate](#itemformurltemplate)	 
----
**Descrizione:** Template per comporre l'url della scheda articolo online	 
**Tipo:** Template	 
[KeywordSearchFields](#keywordsearchfields)	 
----
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
[LiveSearch](#livesearch)	 
----
**Descrizione:** Abilita la ricerca 'live' degli articoli	 
**Tipo:** Boolean	 
[SortFields](#sortfields)	 
----
**Descrizione:** 	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
AdvancedSearchFields 
-----

**Valori:**
* CatalogPriceList
* ErpStatus
* FreeBoolean
* FreeLookup
* ItemCollection
* ItemGroupLevel
* ItemLine
* ItemSeries
* Manufacturer
* Prebuy
* Season
* SeasonGroup
* Trademark

IdEncodingType 
-----

**Valori:**
* 0 => Id
* 1 => Produttore + Codice Articolo Produttore, es. 'BTI 5001'

ItemFormUrlTemplate 
-----

**Valori:**
* Barcode
* ItemId
* ManufacturerItemId

KeywordSearchFields 
-----

**Valori:**
* Description
* Id



SortFields 
-----

**Valori:**
* Description
* Id

