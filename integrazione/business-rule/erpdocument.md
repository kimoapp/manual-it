# ErpDocument

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
      <td style="text-align:left">AdvancedSearchFields</td>
      <td style="text-align:left">Campi per la ricerca avanzata</td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left">
        <p>ErpDocumentType</p>
        <p>ErpLineFreeLookup</p>
        <p>ErpStatus</p>
        <p>Item</p>
        <p>SearchType</p>
      </td>
      <td style="text-align:left">ErpDocumentType</td>
    </tr>
    <tr>
      <td style="text-align:left">FilterPerUser</td>
      <td style="text-align:left">Modalità di filtro dei documenti in base all'utente</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Applica i filtri di default</p>
        <p>1 => Filtra i documenti per 'proprietario' (owner)</p>
        <p>2 => Filtra le righe dei documenti per 'proprietario' (owner), mostrando
          comunque le testate</p>
      </td>
      <td style="text-align:left">1</td>
    </tr>
    <tr>
      <td style="text-align:left">ItemLiveSearch</td>
      <td style="text-align:left">Abilita la ricerca 'live' degli articoli</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">True</td>
    </tr>
    <tr>
      <td style="text-align:left">KeywordSearchFields</td>
      <td style="text-align:left">Campi per la ricerca testuale</td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left">
        <p>AccountName</p>
        <p>Number</p>
      </td>
      <td style="text-align:left">Number|AccountName</td>
    </tr>
  </tbody>
</table>