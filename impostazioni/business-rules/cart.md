# Cart

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](cart.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**CsvDelimiterChar**](cart.md#csvdelimiterchar) | Carattere separatore utilizzato nel report CSV |
| [**CsvSchema**](cart.md#csvschema) | Definizione schema del report Csv del carrello |
| [**KeywordSearchFields**](cart.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**Timeframes**](cart.md#timeframes) | Periodi |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ShowOnlyAssignedToCurrentSalesAgent\|Timeframe  
**Valori:**

* ShowOnlyAssignedToCurrentSalesAgent
* Timeframe

## CsvDelimiterChar

**Tipo:** String

## CsvSchema

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

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** AccountFullName\|CartName\|UserFullName  
**Valori:**

* AccountCode
* AccountFullName
* CartName
* UserFullName

## Timeframes

**Tipo:** Valori separati da pipe  
**Valore di default:** LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12
