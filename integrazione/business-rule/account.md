# Account
**[AdvancedSearchFields](#advancedsearchfields)**	 
**Descrizione:** Campi per la ricerca avanzata	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** CustomerGroup&#124;AddressCity&#124;AddressPostCode&#124;AddressCountrySubdivision	 
[FiscalCodeMandatoryIfIsPerson](#fiscalcodemandatoryifisperson)	 
**Descrizione:** Il Codice Fiscale è obbligatorio se il cliente è una persona fisica	 
**Tipo:** Boolean	 
[KeywordSearchFields](#keywordsearchfields)	 
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Code&#124;Name	 
[SalesConditionDiscountsSearchTypes](#salesconditiondiscountssearchtypes)	 
**Descrizione:** Tipi di condizioni di vendita da mostrare nella funzione 'Sconti per condizioni di vendita'	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** All	 
[VatNumberMandatoryIfIsOrganization](#vatnumbermandatoryifisorganization)	 
**Descrizione:** La Partita IVA è obbligatoria se il cliente è un'organizzazione	 
**Tipo:** Boolean	 
AdvancedSearchFields 
-----

**Valori:**
* AccountFilter
* AddressCity
* AddressCountry
* AddressCountrySubdivision
* AddressPostCode
* CustomerGroup
* FreeLookup
* GeoDistance
* PlaceFreeText
* PlaceType
* ProspectStatus => Tipo di account (prospect, cliente, ...)
* StatisticClass
* Zone



KeywordSearchFields 
-----

**Valori:**
* Code
* FreeText
* Id
* Name

SalesConditionDiscountsSearchTypes 
-----

**Valori:**
* All
* CustomerManufacturer
* Manufacturer

