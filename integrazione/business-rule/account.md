# Account
| Valore| Descrizione |
| --- | --- |
| **[AdvancedSearchFields](#advancedsearchfields)** | Campi per la ricerca avanzata |
| **[FiscalCodeMandatoryIfIsPerson](#fiscalcodemandatoryifisperson)** | Il Codice Fiscale è obbligatorio se il cliente è una persona fisica |
| **[KeywordSearchFields](#keywordsearchfields)** | Campi per la ricerca testuale |
| **[SalesConditionDiscountsSearchTypes](#salesconditiondiscountssearchtypes)** | Tipi di condizioni di vendita da mostrare nella funzione 'Sconti per condizioni di vendita' |
| **[VatNumberMandatoryIfIsOrganization](#vatnumbermandatoryifisorganization)** | La Partita IVA è obbligatoria se il cliente è un'organizzazione |

AdvancedSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** CustomerGroup&#124;AddressCity&#124;AddressPostCode&#124;AddressCountrySubdivision	 
**Valori:**
* AccountFilter
* AddressCity
* AddressCountry
* AddressCountrySubdivision
* AddressPostCode
* CustomerGroup
* ErpStatus
* FreeLookup
* GeoDistance
* PlaceFreeText
* PlaceType
* ProspectStatus => Tipo di account (prospect, cliente, ...)
* StatisticClass
* Zone

FiscalCodeMandatoryIfIsPerson 
-----
**Tipo:** Boolean	 

KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Code&#124;Name	 
**Valori:**
* Code
* FreeText
* Id
* Name

SalesConditionDiscountsSearchTypes 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** All	 
**Valori:**
* All
* CustomerManufacturer
* Manufacturer

VatNumberMandatoryIfIsOrganization 
-----
**Tipo:** Boolean

