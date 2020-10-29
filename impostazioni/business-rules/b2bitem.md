# B2b\Item

| Valore | Descrizione |
| :--- | :--- |
| [**FacetElementsSorting**](b2bitem.md#facetelementssorting) | Tipo di ordinamento dei valori dei facets |
| [**Facets**](b2bitem.md#facets) | Facets |
| [**FacetsWithoutOthersAggregation**](b2bitem.md#facetswithoutothersaggregation) | Facets su cui nascondere la voce "Altri" |
| [**Filters**](b2bitem.md#filters) | Filtri |
| [**FuzzinessPrefixLength**](b2bitem.md#fuzzinessprefixlength) | Numero di caratteri iniziali da non considerare come errori di digitazione |
| [**GroupByAssociatedItems**](b2bitem.md#groupbyassociateditems) | Indica se nei risultati della ricerca gli articoli debbono essere mostrati raggruppati |
| [**KeywordSearchFields**](b2bitem.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**KeywordSearchFieldsWithWeight**](b2bitem.md#keywordsearchfieldswithweight) | Campi per la ricerca testuale pesata |
| [**SearchOperator**](b2bitem.md#searchoperator) | Operatore per la ricerca sul catalogo |
| [**SearchType**](b2bitem.md#searchtype) | Tipo di ricerca sul catalogo |
| [**SortFields**](b2bitem.md#sortfields) | Campi per l'ordinamento |

## FacetElementsSorting

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Alphabetical
* 1 =&gt; Numeric

## Facets

**Tipo:** Valori separati da pipe  
**Valori:**

* ErpStatus
* FreeBoolean
* FreeBooleanSwitch
* FreeLookup
* ItemCollection
* ItemGroups
* ItemLine
* ItemSpecificationGroups
* Manufacturer
* Season
* Trademark

## FacetsWithoutOthersAggregation

**Tipo:** Valori separati da pipe  
**Valori:**

* ErpStatus
* FreeBoolean
* FreeBooleanSwitch
* FreeLookup
* ItemCollection
* ItemGroups
* ItemLine
* ItemSpecificationGroups
* Manufacturer
* Season
* Trademark

## Filters

**Tipo:** Valori separati da pipe  
**Valori:**

* ItemGroupLevel

## FuzzinessPrefixLength

**Tipo:** Int32  
**Valore di default:** 0

## GroupByAssociatedItems

**Tipo:** Boolean

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Id\|Description

## KeywordSearchFieldsWithWeight

**Tipo:** Valori separati da pipe  
**Valore di default:** {'Id': 1.0, 'Description': 1.0}

## SearchOperator

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Or
* 1 =&gt; And

## SearchType

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Ricerca standard
* 1 =&gt; Ricerca tramite ElasticSearch

## SortFields

**Tipo:** Valori separati da pipe  
**Valori:**

* Item.Description
* Item.Id

