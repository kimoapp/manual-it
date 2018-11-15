# Item
| Valore| Descrizione |
| --- | --- |
| **[AdvancedSearchFields](#advancedsearchfields)** | Campi per la ricerca avanzata |
| **[IdEncodingType](#idencodingtype)** | Modalità di codifica dei codici articoli |
| **[ItemFormUrlTemplate](#itemformurltemplate)** | Template per comporre l'url della scheda articolo online |
| **[KeywordSearchFields](#keywordsearchfields)** | Campi per la ricerca testuale |
| **[LiveSearch](#livesearch)** | Abilita la ricerca 'live' degli articoli |
| **[SortFields](#sortfields)** |  |

AdvancedSearchFields 
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

IdEncodingType 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Id
* 1 => Produttore + Codice Articolo Produttore, es. 'BTI 5001'

ItemFormUrlTemplate 
-----
**Tipo:** Template	 
**Valori:**
* Barcode
* ItemId
* ManufacturerItemId

KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
**Valori:**
* Description
* Id

LiveSearch 
-----
**Tipo:** Boolean	 

SortFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Id&#124;Description	 
**Valori:**
* Description
* Id

