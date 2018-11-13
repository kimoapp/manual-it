# Item
AdvancedSearchFields 
----
**Descrizione:** Campi per la ricerca avanzata <br>
**Tipo:** Valori separati da pipe <br>
**Valore di default:** ItemGroupLevel1&#124;ItemGroupLevel2 <br>
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
----
**Descrizione:** Modalità di codifica dei codici articoli <br>
**Tipo:** Enum <br>
**Valore di default:** 0 <br>
**Valori:**
* 0 => Id
* 1 => Produttore + Codice Articolo Produttore, es. 'BTI 5001'

ItemFormUrlTemplate 
----
**Descrizione:** Template per comporre l'url della scheda articolo online <br>
**Tipo:** Template <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**
* Barcode
* ItemId
* ManufacturerItemId

KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale <br>
**Tipo:** Valori separati da pipe <br>
**Valore di default:** Id&#124;Description <br>
**Valori:**
* Description
* Id

LiveSearch 
----
**Descrizione:** Abilita la ricerca 'live' degli articoli <br>
**Tipo:** Boolean <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

SortFields 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Valori separati da pipe <br>
**Valore di default:** Id&#124;Description <br>
**Valori:**
* Description
* Id

