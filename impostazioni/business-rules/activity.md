# Activity

| Valore| Descrizione |
| :--- | :--- |
| [**ActivitiesToUpload**](#activitiestoupload)** | Tipi di attività da inviare al server |
| [**ActivityFromBudgetLineEntityDescriptionTemplate**](#activityfrombudgetlineentitydescriptiontemplate)** | Template per la descrizione delle attività create dalle righe budget |
| [**ActivityFromDocumentEntityDescriptionTemplate**](#activityfromdocumententitydescriptiontemplate)** | Template per la descrizione delle attività create dai Documenti |
| [**ActivityFromErpDocumentEntityDescriptionTemplate**](#activityfromerpdocumententitydescriptiontemplate)** | Template per la descrizione delle attività create dai Documenti da Erp |
| [**CanCreateActivitiesWithoutAccount**](#cancreateactivitieswithoutaccount)** | È possibile create attività non legate ad un account |
| [**CanEditCompletedActivitiesFromErp**](#caneditcompletedactivitiesfromerp)** | È possibile modificare attività che arrivano dal Sistema Esterno come completate |
| [**KeywordSearchFields**](#keywordsearchfields)** | Campi per la ricerca testuale |
| [**ShouldFilterByUserTrademarks**](#shouldfilterbyusertrademarks)** | Indica se le attività vanno filtrare (in fase di sync) inviando ad un utente solo quelle dei trademark per cui è abilitato |

$h2 ActivitiesToUpload 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Solo le attività chiuse
* 1 => Tutte

$h2 ActivityFromBudgetLineEntityDescriptionTemplate 
-----
**Tipo:** Template	 
**Valore di default:** ${BudgetLineId}	 
**Valori:**
* BudgetDescription
* BudgetLineId
* BudgetSeason
* BudgetSeasonId
* BudgetTrademark
* BudgetTrademarkId

$h2 ActivityFromDocumentEntityDescriptionTemplate 
-----
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

$h2 ActivityFromErpDocumentEntityDescriptionTemplate 
-----
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

$h2 CanCreateActivitiesWithoutAccount 
-----
**Tipo:** Boolean	 
**Valore di default:** True	 

$h2 CanEditCompletedActivitiesFromErp 
-----
**Tipo:** Boolean	 
**Valore di default:** True	 

$h2 KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Account.Code&#124;Account.Name&#124;Account.Name2	 
**Valori:**
* Account.Code
* Account.Name

$h2 ShouldFilterByUserTrademarks 
-----
**Tipo:** Boolean

