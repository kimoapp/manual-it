# Cart

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](cart.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**CarLinesExportationFileType**](cart.md#carlinesexportationfiletype) | Tipo di report da usare |
| [**CartLinesExportationFields**](cart.md#cartlinesexportationfields) | Definizione schema del report del carrello |
| [**CartLinesSortingType**](cart.md#cartlinessortingtype) | Tipo di ordinamento delle righe carrello |
| [**CsvDelimiterChar**](cart.md#csvdelimiterchar) | Carattere separatore utilizzato nel report CSV |
| [**KeywordSearchFields**](cart.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**ShouldIgnoreAvailabilitySalesControlsAccordingToLoseRemaining**](cart.md#shouldignoreavailabilitysalescontrolsaccordingtoloseremaining) | Ignora i controlli commerciali sulle disponibilità in assenza della perdita residuo |
| [**Timeframes**](cart.md#timeframes) | Periodi |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ShowOnlyAssignedToCurrentSalesAgent\|Timeframe  
**Valori:**

* ShowOnlyAssignedToCurrentSalesAgent
* Timeframe

## CarLinesExportationFileType

**Tipo:** String  
**Valore di default:** Csv

## CartLinesExportationFields

**Tipo:** Valori separati da pipe  
**Valore di default:** CartName\|LineNumber\|DocumentDate\|ItemId\|ItemDescription\|SalesQty\|LineNotes\|UnitPrice\|NetUnitPrice\|LineDiscounts  
**Valori:**

* CartAmount
* CartName
* CollectOnSite
* CollectOnSiteDateTime
* DeliveryDate
* DocumentDate
* ItemDescription
* ItemFreeText1
* ItemFreeText2
* ItemFreeText3
* ItemFreeText4
* ItemFreeText5
* ItemId
* LineAmount
* LineCollectOnSite
* LineCollectOnSiteDateTime
* LineDiscount1
* LineDiscount2
* LineDiscount3
* LineDiscount4
* LineDiscount5
* LineDiscount6
* LineDiscount7
* LineDiscounts
* LineNotes
* LineNumber
* NetUnitPrice
* Notes
* SalesQty
* UnitPrice
* Variable1Id
* Variable2Id
* VariableValue1Id
* VariableValue2Id

## CartLinesSortingType

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Reversed
* 1 =&gt; Standard

## CsvDelimiterChar

**Tipo:** String

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** AccountFullName\|CartName\|UserFullName  
**Valori:**

* AccountCode
* AccountFullName
* CartName
* UserFullName

## ShouldIgnoreAvailabilitySalesControlsAccordingToLoseRemaining

**Tipo:** Enum  
**Valori:**

* 0 =&gt; No
* 1 =&gt; WhenLoseRemainingIsFalse
* 2 =&gt; WhenLoseRemainingIsTrue

## Timeframes

**Tipo:** Valori separati da pipe  
**Valore di default:** LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12
