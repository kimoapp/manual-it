# Item

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](item.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**BitwiseFreeBooleanField**](item.md#bitwisefreebooleanfield) | Campo da utilizzare per la gestione dei BitwiseFreeBoolean |
| [**BitwiseFreeBooleanFieldTranlsations**](item.md#bitwisefreebooleanfieldtranlsations) |  |
| [**CatalogViewMode**](item.md#catalogviewmode) | Modalità di codifica dei codici articoli |
| [**IdEncodingType**](item.md#idencodingtype) | Modalità di codifica dei codici articoli |
| [**ItemFormUrlTemplate**](item.md#itemformurltemplate) | Template per comporre l'url della scheda articolo online |
| [**KeywordSearchFields**](item.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**LiveSearch**](item.md#livesearch) | Abilita la ricerca 'live' degli articoli |
| [**ScanBarcodesViaCamera**](item.md#scanbarcodesviacamera) | Abilita la ricerca dei barcode attraverso la fotocamera del dispositivo |
| [**SortFields**](item.md#sortfields) |  |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ItemGroupLevel1\|ItemGroupLevel2  
**Valori:**

* Barcode
* BitwiseFreeBoolean
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

## BitwiseFreeBooleanField

**Tipo:** String

## BitwiseFreeBooleanFieldTranlsations

**Tipo:** Valori separati da pipe

## CatalogViewMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Default
* 1 =&gt; Wizard

## IdEncodingType

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Id
* 1 =&gt; Produttore + Codice Articolo Produttore, es. 'BTI 5001'

## ItemFormUrlTemplate

**Tipo:** Template  
**Valori:**

* Barcode
* ItemId
* ManufacturerItemId

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Id\|Description  
**Valori:**

* Description
* Id

## LiveSearch

**Tipo:** Boolean

## ScanBarcodesViaCamera

**Tipo:** Boolean

## SortFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Id\|Description  
**Valori:**

* Description
* Id
.