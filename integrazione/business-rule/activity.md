# Activity
ActivitiesToUpload 
----
**Descrizione:** Tipi di attività da inviare al server	 
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Solo le attività chiuse
* 1 => Tutte

ActivityFromBudgetLineEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dalle righe budget	 
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
----
**Descrizione:** Template per la descrizione delle attività create dai Documenti	 
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
----
**Descrizione:** Template per la descrizione delle attività create dai Documenti da Erp	 
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
----
**Descrizione:** È possibile create attività non legate ad un account	 
**Tipo:** Boolean	 
**Valore di default:** True	 

CanEditCompletedActivitiesFromErp 
----
**Descrizione:** È possibile modificare attività che arrivano dal Sistema Esterno come completate	 
**Tipo:** Boolean	 
**Valore di default:** True	 

KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale	 
**Tipo:** Valori separati da pipe	 
**Valore di default:** Account.Code&#124;Account.Name	 
**Valori:**
* Account.Code
* Account.Name

