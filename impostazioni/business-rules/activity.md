# Activity

| Valore | Descrizione |
| :--- | :--- |
| [**ActivitiesToUpload**](activity.md#activitiestoupload) | Tipi di attività da inviare al server |
| [**ActivityFromBudgetLineEntityDescriptionTemplate**](activity.md#activityfrombudgetlineentitydescriptiontemplate) | Template per la descrizione delle attività create dalle righe budget |
| [**ActivityFromDocumentEntityDescriptionTemplate**](activity.md#activityfromdocumententitydescriptiontemplate) | Template per la descrizione delle attività create dai Documenti |
| [**ActivityFromErpDocumentEntityDescriptionTemplate**](activity.md#activityfromerpdocumententitydescriptiontemplate) | Template per la descrizione delle attività create dai Documenti da Erp |
| [**AdvancedSearchFields**](activity.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**CanCreateActivitiesWithoutAccount**](activity.md#cancreateactivitieswithoutaccount) | È possibile create attività non legate ad un account |
| [**CanEditCompletedActivitiesFromErp**](activity.md#caneditcompletedactivitiesfromerp) | È possibile modificare attività che arrivano dal Sistema Esterno come completate |
| [**EntitiesToUploadOnSave**](activity.md#entitiestouploadonsave) | Entità da inviare al server durante il salvataggio di un attività |
| [**KeywordSearchFields**](activity.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**ShouldFilterByUserTrademarks**](activity.md#shouldfilterbyusertrademarks) | Indica se le attività vanno filtrare \(in fase di sync\) inviando ad un utente solo quelle dei trademark per cui è abilitato |

## ActivitiesToUpload

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Solo le attività chiuse
* 1 =&gt; Tutte

## ActivityFromBudgetLineEntityDescriptionTemplate

**Tipo:** Template  
**Valore di default:** ${BudgetLineId}  
**Valori:**

* BudgetDescription
* BudgetLineId
* BudgetSeason
* BudgetSeasonId
* BudgetTrademark
* BudgetTrademarkId

## ActivityFromDocumentEntityDescriptionTemplate

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

## ActivityFromErpDocumentEntityDescriptionTemplate

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

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:**   
**Valori:**

* User

## CanCreateActivitiesWithoutAccount

**Tipo:** Boolean  
**Valore di default:** True

## CanEditCompletedActivitiesFromErp

**Tipo:** Boolean  
**Valore di default:** True

## EntitiesToUploadOnSave

**Tipo:** Valori separati da pipe

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Account.Code\|Account.Name\|Account.Name2  
**Valori:**

* Account.Code
* Account.Name

## ShouldFilterByUserTrademarks

**Tipo:** Boolean
