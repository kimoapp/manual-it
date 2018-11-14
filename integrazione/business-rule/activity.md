# Activity
[ActivitiesToUpload](#activitiestoupload)	 
**Descrizione:** Tipi di attività da inviare al server	 
**Tipo:** Enum	 
**Valore di default:** 0	 
[ActivityFromBudgetLineEntityDescriptionTemplate](#activityfrombudgetlineentitydescriptiontemplate)	 
**Descrizione:** Template per la descrizione delle attività create dalle righe budget	 
**Tipo:** Template	 
**Valore di default:** ${BudgetLineId}	 
[ActivityFromDocumentEntityDescriptionTemplate](#activityfromdocumententitydescriptiontemplate)	 
**Descrizione:** Template per la descrizione delle attività create dai Documenti	 
**Tipo:** Template	 
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}	 
[ActivityFromErpDocumentEntityDescriptionTemplate](#activityfromerpdocumententitydescriptiontemplate)	 
**Descrizione:** Template per la descrizione delle attività create dai Documenti da Erp	 
**Tipo:** Template	 
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}	 
[CanCreateActivitiesWithoutAccount](#cancreateactivitieswithoutaccount)	 
**Descrizione:** È possibile create attività non legate ad un account	 
**Tipo:** Boolean	 
**Valore di default:** True	 
[CanEditCompletedActivitiesFromErp](#caneditcompletedactivitiesfromerp)	 
**Descrizione:** È possibile modificare attività che arrivano dal Sistema Esterno come completate	 
**Tipo:** Boolean	 
**Valore di default:** True	 
[KeywordSearchFields](#keywordsearchfields)	 
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Account.Code&#124;Account.Name	 
ActivitiesToUpload 
-----

**Valori:**
* 0 => Solo le attività chiuse
* 1 => Tutte

ActivityFromBudgetLineEntityDescriptionTemplate 
-----

**Valori:**
* BudgetDescription
* BudgetLineId
* BudgetSeason
* BudgetSeasonId
* BudgetTrademark
* BudgetTrademarkId

ActivityFromDocumentEntityDescriptionTemplate 
-----

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

**Valori:**
* DocumentDate
* DocumentId
* DocumentNumber
* DocumentReference
* DocumentTypeCode
* DocumentTypeDescription
* DocumentTypeId





KeywordSearchFields 
-----

**Valori:**
* Account.Code
* Account.Name

