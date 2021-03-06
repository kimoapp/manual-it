# ErpDocument

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](erpdocument.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**FilterPerUser**](erpdocument.md#filterperuser) | Modalità di filtro dei documenti in base all'utente |
| [**ItemLiveSearch**](erpdocument.md#itemlivesearch) | Abilita la ricerca 'live' degli articoli |
| [**KeywordSearchFields**](erpdocument.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**Timeframes**](erpdocument.md#timeframes) | Periodi |
| [**TotalAmountType**](erpdocument.md#totalamounttype) | Tipo di totale da visualizzare nel footer |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ErpDocumentType\|Timeframe  
**Valori:**

* ErpDocumentType
* ErpLineFreeLookup
* ErpStatus
* FreeLookup
* FulfillmentStatus
* Item
* SalesAgent
* SearchType
* Timeframe

## FilterPerUser

**Tipo:** Enum  
**Valore di default:** 1  
**Valori:**

* 0 =&gt; Applica i filtri di default
* 1 =&gt; Filtra i documenti per 'proprietario' \(owner\)
* 2 =&gt; Filtra le righe dei documenti per 'proprietario' \(owner\), mostrando comunque le testate

## ItemLiveSearch

**Tipo:** Boolean  
**Valore di default:** True

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Number\|AccountName\|AccountName2  
**Valori:**

* AccountName
* Number

## Timeframes

**Tipo:** Valori separati da pipe  
**Valore di default:** LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12

## TotalAmountType

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Amount
* 1 =&gt; AmountIncludingVat

