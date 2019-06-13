# Account

| Valore| Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](account.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**FiscalCodeMandatoryIfIsPerson**](account.md#fiscalcodemandatoryifisperson) | Il Codice Fiscale è obbligatorio se il cliente è una persona fisica |
| [**KeywordSearchFields**](account.md#keywordsearchfields) | Campi per la ricerca testuale |
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
* ErpStatus
* FreeLookup
* GeoDistance
* PlaceFreeText
* PlaceType
* ProspectStatus =&gt; Tipo di account \(prospect, cliente, ...\)
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

## SalesConditionDiscountsSearchTypes 

**Tipo:** Valori separati da pipe	 
**Valore di default:** All	 
**Valori:**

* All
* CustomerManufacturer
* Manufacturer

## VatNumberMandatoryIfIsOrganization 

**Tipo:** Boolean	 



