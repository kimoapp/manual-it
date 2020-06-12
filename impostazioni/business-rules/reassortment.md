# Reassortment

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](reassortment.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**KeywordSearchFields**](reassortment.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**ShipmentSiteFilterMode**](reassortment.md#shipmentsitefiltermode) | Indica se i riassortimenti devono essere filtrati o meno per la destinazione merci |
| [**ShowItemInDocumentMode**](reassortment.md#showitemindocumentmode) | Indica la modalità con cui mostrare se un articolo è già stato inserito nei documenti di vendita |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ShipmentSiteFilterMode\|ItemGroupLevel1\|ItemGroupLevel2

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ReassortmentLine.ItemId\|ReassortmentLine.ItemDescription  
**Valori:**

* CatalogPriceList
* ErpStatus
* FreeBoolean
* ItemCollection
* ItemLine
* ItemSeries
* Manufacturer
* Prebuy
* Season
* SeasonGroup
* Trademark

## ShipmentSiteFilterMode

**Tipo:** Enum  
**Valori:**

* 0 =&gt; DoNotFilterByShipmentSite
* 1 =&gt; FilterByShipmentSite

## ShowItemInDocumentMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; ByItem
* 1 =&gt; ByReassortmentLine
