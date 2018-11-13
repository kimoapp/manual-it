# Activity

<br><br> 

ActivitiesToUpload 
---
<br> Tipi di attività da inviare al server <br> 
Enum <br> 
0 <br>
<ul> 
<li>0 => Solo le attività chiuse</li>
<li>1 => Tutte</li>
</ul>
ActivityFromBudgetLineEntityDescriptionTemplate 
---
<br> Template per la descrizione delle attività create dalle righe budget <br> 
Template <br> 
${BudgetLineId} <br>
<ul> 
<li>BudgetDescription</li>
<li>BudgetLineId</li>
<li>BudgetSeason</li>
<li>BudgetSeasonId</li>
<li>BudgetTrademark</li>
<li>BudgetTrademarkId</li>
</ul>
ActivityFromDocumentEntityDescriptionTemplate 
---
<br> Template per la descrizione delle attività create dai Documenti <br> 
Template <br> 
${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} <br>
<ul> 
<li>DocumentDate</li>
<li>DocumentId</li>
<li>DocumentNumber</li>
<li>DocumentReference</li>
<li>DocumentTypeCode</li>
<li>DocumentTypeDescription</li>
<li>DocumentTypeId</li>
</ul>
ActivityFromErpDocumentEntityDescriptionTemplate 
---
<br> Template per la descrizione delle attività create dai Documenti da Erp <br> 
Template <br> 
${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} <br>
<ul> 
<li>DocumentDate</li>
<li>DocumentId</li>
<li>DocumentNumber</li>
<li>DocumentReference</li>
<li>DocumentTypeCode</li>
<li>DocumentTypeDescription</li>
<li>DocumentTypeId</li>
</ul>
CanCreateActivitiesWithoutAccount 
---
<br> È possibile create attività non legate ad un account <br> 
Boolean <br> 
True <br>
<ul> 
</ul>
CanEditCompletedActivitiesFromErp 
---
<br> È possibile modificare attività che arrivano dal Sistema Esterno come completate <br> 
Boolean <br> 
True <br>
<ul> 
</ul>
KeywordSearchFields 
---
<br> Campi per la ricerca testuale <br> 
Valori separati da pipe <br> 
Account.Code&#124;Account.Name <br>
<ul> 
<li>Account.Code</li>
<li>Account.Name</li>
</ul>

