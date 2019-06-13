# Activity

| Valore | Descrizione |
| :--- | :--- |
| [**ActivitiesToUpload**](activity.md#activitiestoupload)\*\* | Tipi di attività da inviare al server |
| [**ActivityFromBudgetLineEntityDescriptionTemplate**](activity.md#activityfrombudgetlineentitydescriptiontemplate)\*\* | Template per la descrizione delle attività create dalle righe budget |
| [**ActivityFromDocumentEntityDescriptionTemplate**](activity.md#activityfromdocumententitydescriptiontemplate)\*\* | Template per la descrizione delle attività create dai Documenti |
| [**ActivityFromErpDocumentEntityDescriptionTemplate**](activity.md#activityfromerpdocumententitydescriptiontemplate)\*\* | Template per la descrizione delle attività create dai Documenti da Erp |
| [**CanCreateActivitiesWithoutAccount**](activity.md#cancreateactivitieswithoutaccount)\*\* | È possibile create attività non legate ad un account |
| [**CanEditCompletedActivitiesFromErp**](activity.md#caneditcompletedactivitiesfromerp)\*\* | È possibile modificare attività che arrivano dal Sistema Esterno come completate |
| [**KeywordSearchFields**](activity.md#keywordsearchfields)\*\* | Campi per la ricerca testuale |
| [**ShouldFilterByUserTrademarks**](activity.md#shouldfilterbyusertrademarks)\*\* | Indica se le attività vanno filtrare \(in fase di sync\) inviando ad un utente solo quelle dei trademark per cui è abilitato |

## $h2 ActivitiesToUpload

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Solo le attività chiuse
* 1 =&gt; Tutte

## $h2 ActivityFromBudgetLineEntityDescriptionTemplate

**Tipo:** Template  
**Valore di default:** ${BudgetLineId}  
**Valori:**

* BudgetDescription
* BudgetLineId
* BudgetSeason
* BudgetSeasonId
* BudgetTrademark
* BudgetTrademarkId

## $h2 ActivityFromDocumentEntityDescriptionTemplate

**Tipo:** Template  
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}  
**Valori:**

* DocumentDate
* DocumentId
* DocumentNumber
* DocumentReference
* DocumentTypeCode
* DocumentTypeDescription
* DocumentTypeId

## $h2 ActivityFromErpDocumentEntityDescriptionTemplate

**Tipo:** Template  
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}  
**Valori:**

* DocumentDate
* DocumentId
* DocumentNumber
* DocumentReference
* DocumentTypeCode
* DocumentTypeDescription
* DocumentTypeId

## $h2 CanCreateActivitiesWithoutAccount

**Tipo:** Boolean  
**Valore di default:** True

## $h2 CanEditCompletedActivitiesFromErp

**Tipo:** Boolean  
**Valore di default:** True

## $h2 KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Account.Code\|Account.Name\|Account.Name2  
**Valori:**

* Account.Code
* Account.Name

## $h2 ShouldFilterByUserTrademarks

**Tipo:** Boolean

