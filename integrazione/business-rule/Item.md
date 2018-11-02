# Item

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| AdvancedSearchFields | Campi per la ricerca avanzata | Valori separati da pipe | <ul>  <li>CatalogPriceList</li> <li>ErpStatus</li> <li>FreeBoolean</li> <li>FreeLookup</li> <li>ItemCollection</li> <li>ItemGroupLevel</li> <li>ItemLine</li> <li>ItemSeries</li> <li>Manufacturer</li> <li>Prebuy</li> <li>Season</li> <li>SeasonGroup</li> <li>Trademark</li></ul>| ItemGroupLevel1&#124;ItemGroupLevel2 |
| IdEncodingType | Modalità di codifica dei codici articoli | Enum | <ul>  <li>0 => Id</li> <li>1 => Produttore + Codice Articolo Produttore, es. 'BTI 5001'</li></ul>| 0 |
| ItemFormUrlTemplate | Template per comporre l'url della scheda articolo online | Template | <ul>  <li>Barcode</li> <li>ItemId</li> <li>ManufacturerItemId</li></ul>|  |
| KeywordSearchFields | Campi per la ricerca testuale | Valori separati da pipe | <ul>  <li>Description</li> <li>Id</li></ul>| Id&#124;Description |
| LiveSearch | Abilita la ricerca 'live' degli articoli | Boolean | <ul> </ul>|  |
| SortFields |  | Valori separati da pipe | <ul>  <li>Description</li> <li>Id</li></ul>| Id&#124;Description |

