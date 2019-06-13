# Item

| Valore| Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](#advancedsearchfields)** | Campi per la ricerca avanzata |
| [**IdEncodingType**](#idencodingtype)** | Modalità di codifica dei codici articoli |
| [**ItemFormUrlTemplate**](#itemformurltemplate)** | Template per comporre l'url della scheda articolo online |
| [**KeywordSearchFields**](#keywordsearchfields)** | Campi per la ricerca testuale |
| [**LiveSearch**](#livesearch)** | Abilita la ricerca 'live' degli articoli |
| [**SortFields**](#sortfields)** |  |

$h2 AdvancedSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** ItemGroupLevel1&#124;ItemGroupLevel2	 
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

$h2 IdEncodingType 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Id
* 1 => Produttore + Codice Articolo Produttore, es. 'BTI 5001'

$h2 ItemFormUrlTemplate 
-----
**Tipo:** Template	 
**Valori:**
* Barcode
* ItemId
* ManufacturerItemId

$h2 KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
**Valori:**
* Description
* Id

$h2 LiveSearch 
-----
**Tipo:** Boolean	 

$h2 SortFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
**Valori:**
* Description
* Id

