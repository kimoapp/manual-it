# Activity
ActivitiesToUpload 
----
**Descrizione:** Tipi di attività da inviare al server <br>
**Tipo:** Enum <br>
**Valore di default:** 0 <br>
**Valori:**
* 0 => Solo le attività chiuse
* 1 => Tutte

ActivityFromBudgetLineEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dalle righe budget <br>
**Tipo:** Template <br>
**Valore di default:** ${BudgetLineId} <br>
**Valori:**
* BudgetDescription
* BudgetLineId
* BudgetSeason
* BudgetSeasonId
* BudgetTrademark
* BudgetTrademarkId

ActivityFromDocumentEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dai Documenti <br>
**Tipo:** Template <br>
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} <br>
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
**Descrizione:** Template per la descrizione delle attività create dai Documenti da Erp <br>
**Tipo:** Template <br>
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} <br>
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
**Descrizione:** È possibile create attività non legate ad un account <br>
**Tipo:** Boolean <br>
**Valore di default:** True <br>
**Valori:**

CanEditCompletedActivitiesFromErp 
----
**Descrizione:** È possibile modificare attività che arrivano dal Sistema Esterno come completate <br>
**Tipo:** Boolean <br>
**Valore di default:** True <br>
**Valori:**

KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale <br>
**Tipo:** Valori separati da pipe <br>
**Valore di default:** Account.Code&#124;Account.Name <br>
**Valori:**
* Account.Code
* Account.Name

