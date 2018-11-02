# Activity

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| ActivitiesToUpload | Tipi di attività da inviare al server | Enum | <ul>  <li>0 => Solo le attività chiuse</li> <li>1 => Tutte</li></ul>| 0 |
| ActivityFromBudgetLineEntityDescriptionTemplate | Template per la descrizione delle attività create dalle righe budget | Template | <ul>  <li>BudgetDescription</li> <li>BudgetLineId</li> <li>BudgetSeason</li> <li>BudgetSeasonId</li> <li>BudgetTrademark</li> <li>BudgetTrademarkId</li></ul>| ${BudgetLineId} |
| ActivityFromDocumentEntityDescriptionTemplate | Template per la descrizione delle attività create dai Documenti | Template | <ul>  <li>DocumentDate</li> <li>DocumentId</li> <li>DocumentNumber</li> <li>DocumentReference</li> <li>DocumentTypeCode</li> <li>DocumentTypeDescription</li> <li>DocumentTypeId</li></ul>| ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} |
| ActivityFromErpDocumentEntityDescriptionTemplate | Template per la descrizione delle attività create dai Documenti da Erp | Template | <ul>  <li>DocumentDate</li> <li>DocumentId</li> <li>DocumentNumber</li> <li>DocumentReference</li> <li>DocumentTypeCode</li> <li>DocumentTypeDescription</li> <li>DocumentTypeId</li></ul>| ${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate} |
| CanCreateActivitiesWithoutAccount | È possibile create attività non legate ad un account | Boolean | <ul> </ul>| True |
| CanEditCompletedActivitiesFromErp | È possibile modificare attività che arrivano dal Sistema Esterno come completate | Boolean | <ul> </ul>| True |
| KeywordSearchFields | Campi per la ricerca testuale | Valori separati da pipe | <ul>  <li>Account.Code</li> <li>Account.Name</li></ul>| Account.Code&#124;Account.Name |

