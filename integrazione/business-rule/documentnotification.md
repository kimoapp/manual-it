# DocumentNotification

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
      <td style="text-align:left">OnConfirmedDocumentTypes</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedMailBccRecipients</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">String</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedMailBodyTemplate</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Template</td>
      <td style="text-align:left">
        <p>AccountCode</p>
        <p>AccountName</p>
        <p>DocumentAmount</p>
        <p>DocumentAmountIncludingVat</p>
        <p>DocumentDate</p>
        <p>DocumentNumber</p>
        <p>DocumentReference</p>
        <p>DocumentType</p>
        <p>DocumentUrl</p>
      </td>
      <td style="text-align:left">${DocumentType} '${DocumentNumber}' confermato!</td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedMailRecipients</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">String</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedMailSubjectTemplate</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Template</td>
      <td style="text-align:left">
        <p>AccountCode</p>
        <p>AccountName</p>
        <p>DocumentAmount</p>
        <p>DocumentAmountIncludingVat</p>
        <p>DocumentDate</p>
        <p>DocumentNumber</p>
        <p>DocumentReference</p>
        <p>DocumentType</p>
        <p>DocumentUrl</p>
      </td>
      <td style="text-align:left">${DocumentType} '${DocumentNumber}' confermato!</td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedReportType</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">String</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">OnConfirmedSendMailToCreator</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">SendOnConfirmed</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>