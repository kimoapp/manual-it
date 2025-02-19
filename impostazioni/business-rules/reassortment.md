# Reassortment

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](reassortment.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**DocumentContextTitleTemplate**](reassortment.md#documentcontexttitletemplate) |  |
| [**KeywordSearchFields**](reassortment.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**ShipmentSiteFilterMode**](reassortment.md#shipmentsitefiltermode) | Indica se i riassortimenti devono essere filtrati o meno per la destinazione merci |
| [**ShowItemInDocumentMode**](reassortment.md#showitemindocumentmode) | Indica la modalità con cui mostrare se un articolo è già stato inserito nei documenti di vendita |
| [**TitleTemplate**](reassortment.md#titletemplate) |  |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ShipmentSiteFilterMode\|ItemGroupLevel1\|ItemGroupLevel2  
**Valori:**

* BitwiseFreeBoolean
* ItemCollection
* ItemErpStatus
* ItemFreeBoolean
* ItemGroupLevel
* ItemSeries
* Manufacturer
* ShipmentSiteFilterMode
* Trademark

## DocumentContextTitleTemplate

**Tipo:** String

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ReassortmentLine.ItemId\|ReassortmentLine.ItemDescription  
**Valori:**

* ReassortmentLine.ItemDescription
* ReassortmentLine.ItemId

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

## TitleTemplate

**Tipo:** String
