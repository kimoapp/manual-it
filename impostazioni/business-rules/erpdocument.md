# ErpDocument

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](erpdocument.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**EnabledEditOperations**](erpdocument.md#enablededitoperations) | Azioni online abilitate per ciascun tipo di documento da Erp |
| [**ExpectedClosingDatePostponeDays**](erpdocument.md#expectedclosingdatepostponedays) | Numero di giorni proposti durante la posticipazione dei documenti, rispetto alla data di scadenza |
| [**FilterPerUser**](erpdocument.md#filterperuser) | Modalità di filtro dei documenti in base all'utente |
| [**ItemLiveSearch**](erpdocument.md#itemlivesearch) | Abilita la ricerca 'live' degli articoli |
| [**KeywordSearchFields**](erpdocument.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**MaxDaysWithExpiredDocuments**](erpdocument.md#maxdayswithexpireddocuments) | Numero massimo di giorni per cui possono essere consentiti documenti scaduti |
| [**OnlineEditOperationResultMap**](erpdocument.md#onlineeditoperationresultmap) | Mapping tra il risultato delle azioni online restituite dal gestionale e quelli attesi da Kimo |
| [**ShouldAskArchivingReason**](erpdocument.md#shouldaskarchivingreason) | Indica se deve essere richiesta la causale di archiviazione |
| [**Timeframes**](erpdocument.md#timeframes) | Periodi |
| [**TotalAmountType**](erpdocument.md#totalamounttype) | Tipo di totale da visualizzare nel footer |
| [**WarningDaysWithExpiredDocuments**](erpdocument.md#warningdayswithexpireddocuments) | Numero di giorni dopo la scadenza del documento in cui dare un messaggio di warning |

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

## EnabledEditOperations

**Tipo:** Valori separati da pipe  
**Valori:**

* 0 =&gt; Undefined
* 1 =&gt; Archiving
* 2 =&gt; ExpectedClosingDateEdit
* 3 =&gt; ForceLineClosing

## ExpectedClosingDatePostponeDays

**Tipo:** Valori separati da pipe  
**Valore di default:** 1\|5\|10

## FilterPerUser

**Tipo:** Enum  
**Valore di default:** 1  
**Valori:**

* 0 =&gt; Applica i filtri di default
* 1 =&gt; Filtra i documenti per 'proprietario' \(owner\)
* 2 =&gt; Filtra le righe dei documenti per 'proprietario' \(owner\), mostrando comunque le testate
* 3 =&gt; Filtra i documenti in base all'assegnazione definita nella ErpDocumentPerSalesAgent

## ItemLiveSearch

**Tipo:** Boolean  
**Valore di default:** True

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Number\|AccountName\|AccountName2  
**Valori:**

* AccountName
* Number

## MaxDaysWithExpiredDocuments

**Tipo:** Nullable`1

## OnlineEditOperationResultMap

**Tipo:** Enum  
**Valori:**

* 0 =&gt; WaitingForResult
* 1 =&gt; Ok
* 2 =&gt; GenericError
* 3 =&gt; ErpTimedOut
* 4 =&gt; ErpDocumentAlreadyArchivedOnErp
* 5 =&gt; ErpDocumentAlreadyArchivedOnKimo

## ShouldAskArchivingReason

**Tipo:** Boolean

## Timeframes

**Tipo:** Valori separati da pipe  
**Valore di default:** LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12

## TotalAmountType

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Amount
* 1 =&gt; AmountIncludingVat

## WarningDaysWithExpiredDocuments

**Tipo:** Nullable`1
