# Activity

<br><br> 

ActivitiesToUpload 
----
**Descrizione:** Tipi di attività da inviare al server<br>
**Tipo:** Enum<br>
**Valore di default:** 0<br>
**Valori:**
<ul> 
<li>0 => Solo le attività chiuse</li>
<li>1 => Tutte</li>
</ul><br>
ActivityFromBudgetLineEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dalle righe budget<br>
**Tipo:** Template<br>
**Valore di default:** ${BudgetLineId}<br>
**Valori:**
<ul> 
<li>BudgetDescription</li>
<li>BudgetLineId</li>
<li>BudgetSeason</li>
<li>BudgetSeasonId</li>
<li>BudgetTrademark</li>
<li>BudgetTrademarkId</li>
</ul><br>
ActivityFromDocumentEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dai Documenti<br>
**Tipo:** Template<br>
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}<br>
**Valori:**
<ul> 
<li>DocumentDate</li>
<li>DocumentId</li>
<li>DocumentNumber</li>
<li>DocumentReference</li>
<li>DocumentTypeCode</li>
<li>DocumentTypeDescription</li>
<li>DocumentTypeId</li>
</ul><br>
ActivityFromErpDocumentEntityDescriptionTemplate 
----
**Descrizione:** Template per la descrizione delle attività create dai Documenti da Erp<br>
**Tipo:** Template<br>
**Valore di default:** ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}<br>
**Valori:**
<ul> 
<li>DocumentDate</li>
<li>DocumentId</li>
<li>DocumentNumber</li>
<li>DocumentReference</li>
<li>DocumentTypeCode</li>
<li>DocumentTypeDescription</li>
<li>DocumentTypeId</li>
</ul><br>
CanCreateActivitiesWithoutAccount 
----
**Descrizione:** È possibile create attività non legate ad un account<br>
**Tipo:** Boolean<br>
**Valore di default:** True<br>
**Valori:**
<ul> 
</ul><br>
CanEditCompletedActivitiesFromErp 
----
**Descrizione:** È possibile modificare attività che arrivano dal Sistema Esterno come completate<br>
**Tipo:** Boolean<br>
**Valore di default:** True<br>
**Valori:**
<ul> 
</ul><br>
KeywordSearchFields 
----
**Descrizione:** Campi per la ricerca testuale<br>
**Tipo:** Valori separati da pipe<br>
**Valore di default:** Account.Code&#124;Account.Name<br>
**Valori:**
<ul> 
<li>Account.Code</li>
<li>Account.Name</li>
</ul><br>

