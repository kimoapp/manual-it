# Activity

<table>
  <thead>
    <tr>
      <th style="text-align:left">Valore</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Tipo</th>
      <th style="text-align:left">Valori</th>
      <th style="text-align:left">Valore di default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">ActivitiesToUpload</td>
      <td style="text-align:left">Tipi di attività da inviare al server</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Solo le attività chiuse</p>
        <p>1 => Tutte</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">ActivityFromBudgetLineEntityDescriptionTemplate</td>
      <td style="text-align:left">Template per la descrizione delle attività create dalle righe budget</td>
      <td
      style="text-align:left">Template</td>
        <td style="text-align:left">
          <p>BudgetDescription</p>
          <p>BudgetLineId</p>
          <p>BudgetSeason</p>
          <p>BudgetSeasonId</p>
          <p>BudgetTrademark</p>
          <p>BudgetTrademarkId</p>
        </td>
        <td style="text-align:left">${BudgetLineId}</td>
    </tr>
    <tr>
      <td style="text-align:left">ActivityFromDocumentEntityDescriptionTemplate</td>
      <td style="text-align:left">Template per la descrizione delle attività create dai Documenti</td>
      <td
      style="text-align:left">Template</td>
        <td style="text-align:left">
          <p>DocumentDate</p>
          <p>DocumentId</p>
          <p>DocumentNumber</p>
          <p>DocumentReference</p>
          <p>DocumentTypeCode</p>
          <p>DocumentTypeDescription</p>
          <p>DocumentTypeId</p>
        </td>
        <td style="text-align:left">${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}</td>
    </tr>
    <tr>
      <td style="text-align:left">ActivityFromErpDocumentEntityDescriptionTemplate</td>
      <td style="text-align:left">Template per la descrizione delle attività create dai Documenti da Erp</td>
      <td
      style="text-align:left">Template</td>
        <td style="text-align:left">
          <p>DocumentDate</p>
          <p>DocumentId</p>
          <p>DocumentNumber</p>
          <p>DocumentReference</p>
          <p>DocumentTypeCode</p>
          <p>DocumentTypeDescription</p>
          <p>DocumentTypeId</p>
        </td>
        <td style="text-align:left">${DocumentTypeDescription} nr. ${DocumentNumber} del ${DocumentDate}</td>
    </tr>
    <tr>
      <td style="text-align:left">CanCreateActivitiesWithoutAccount</td>
      <td style="text-align:left">È possibile create attività non legate ad un account</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">True</td>
    </tr>
    <tr>
      <td style="text-align:left">CanEditCompletedActivitiesFromErp</td>
      <td style="text-align:left">È possibile modificare attività che arrivano dal Sistema Esterno come
        completate</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">True</td>
    </tr>
    <tr>
      <td style="text-align:left">KeywordSearchFields</td>
      <td style="text-align:left">Campi per la ricerca testuale</td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left">
        <p>Account.Code</p>
        <p>Account.Name</p>
      </td>
      <td style="text-align:left">Account.Code|Account.Name</td>
    </tr>
  </tbody>
</table>