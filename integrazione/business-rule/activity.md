# Activity
| Valore| Descrizione |
| --- | --- |
| **[ActivitiesToUpload](#activitiestoupload)** | Tipi di attività da inviare al server |
| **[ActivityFromBudgetLineEntityDescriptionTemplate](#activityfrombudgetlineentitydescriptiontemplate)** | Template per la descrizione delle attività create dalle righe budget |
| **[ActivityFromDocumentEntityDescriptionTemplate](#activityfromdocumententitydescriptiontemplate)** | Template per la descrizione delle attività create dai Documenti |
| **[ActivityFromErpDocumentEntityDescriptionTemplate](#activityfromerpdocumententitydescriptiontemplate)** | Template per la descrizione delle attività create dai Documenti da Erp |
| **[CanCreateActivitiesWithoutAccount](#cancreateactivitieswithoutaccount)** | È possibile create attività non legate ad un account |
| **[CanEditCompletedActivitiesFromErp](#caneditcompletedactivitiesfromerp)** | È possibile modificare attività che arrivano dal Sistema Esterno come completate |
| **[KeywordSearchFields](#keywordsearchfields)** | Campi per la ricerca testuale |
| **[ShouldFilterByUserTrademarks](#shouldfilterbyusertrademarks)** | Indica se le attività vanno filtrare (in fase di sync) inviando ad un utente solo quelle dei trademark per cui è abilitato |

ActivitiesToUpload 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Solo le attività chiuse
* 1 => Tutte

ActivityFromBudgetLineEntityDescriptionTemplate 
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

ActivityFromDocumentEntityDescriptionTemplate 
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

ActivityFromErpDocumentEntityDescriptionTemplate 
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

CanCreateActivitiesWithoutAccount 
-----
**Tipo:** Boolean	 
**Valore di default:** True	 

CanEditCompletedActivitiesFromErp 
-----
**Tipo:** Boolean	 
**Valore di default:** True	 

KeywordSearchFields 
-----
**Tipo:** Valori separati da pipe	 
**Valore di default:** Account.Code&#124;Account.Name	 
**Valori:**
* Account.Code
* Account.Name

ShouldFilterByUserTrademarks 
-----
**Tipo:** Boolean

