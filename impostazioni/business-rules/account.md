# Account

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](account.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**FiscalCodeMandatoryIfIsPerson**](account.md#fiscalcodemandatoryifisperson) | Il Codice Fiscale è obbligatorio se il cliente è una persona fisica |
| [**KeywordSearchFields**](account.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**PageSize**](account.md#pagesize) | Numero di elementi visualizzati nella ricerca clienti |
| [**SalesConditionDiscountsSearchTypes**](account.md#salesconditiondiscountssearchtypes) | Tipi di condizioni di vendita da mostrare nella funzione 'Sconti per condizioni di vendita' |
| [**VatNumberMandatoryIfIsOrganization**](account.md#vatnumbermandatoryifisorganization) | La Partita IVA è obbligatoria se il cliente è un'organizzazione |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** CustomerGroup\|AddressCity\|AddressPostCode\|AddressCountrySubdivision  
**Valori:**

* AccountFilter
* AddressCity
* AddressCountry
* AddressCountrySubdivision
* AddressPostCode
* CustomerGroup
* CustomerPriceGroup
* ErpStatus
* FreeLookup
* GeoDistance
* PlaceFreeText
* PlaceType
* ProspectStatus =&gt; Tipo di account \(prospect, cliente, ...\)
* SalesAgent
* StatisticClass
* Zone

## FiscalCodeMandatoryIfIsPerson

**Tipo:** Boolean

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Code\|Name\|Name2  
**Valori:**

* Code
* FreeText
* Id
* Name

## PageSize

**Tipo:** Int32  
**Valore di default:** 300

## SalesConditionDiscountsSearchTypes

**Tipo:** Valori separati da pipe  
**Valore di default:** All  
**Valori:**

* All
* CustomerManufacturer
* Manufacturer

## VatNumberMandatoryIfIsOrganization

**Tipo:** Boolean
