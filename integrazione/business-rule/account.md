# Account

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
        <p>AccountFilter</p>
        <p>AddressCity</p>
        <p>AddressCountry</p>
        <p>AddressCountrySubdivision</p>
        <p>AddressPostCode</p>
        <p>CustomerGroup</p>
        <p>FreeLookup</p>
        <p>GeoDistance</p>
        <p>PlaceFreeText</p>
        <p>PlaceType</p>
        <p>ProspectStatus => Tipo di account (prospect, cliente, ...)</p>
        <p>StatisticClass</p>
        <p>Zone</p>
      </td>
      <td style="text-align:left">CustomerGroup|AddressCity|AddressPostCode|AddressCountrySubdivision</td>
    </tr>
    <tr>
      <td style="text-align:left">FiscalCodeMandatoryIfIsPerson</td>
      <td style="text-align:left">Il Codice Fiscale è obbligatorio se il cliente è una persona fisica</td>
      <td
      style="text-align:left">Boolean</td>
        <td style="text-align:left"></td>
        <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">KeywordSearchFields</td>
      <td style="text-align:left">Campi per la ricerca testuale</td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left">
        <p>Code</p>
        <p>FreeText</p>
        <p>Id</p>
        <p>Name</p>
      </td>
      <td style="text-align:left">Code|Name</td>
    </tr>
    <tr>
      <td style="text-align:left">SalesConditionDiscountsSearchTypes</td>
      <td style="text-align:left">Tipi di condizioni di vendita da mostrare nella funzione 'Sconti per condizioni
        di vendita'</td>
      <td style="text-align:left">Valori separati da pipe</td>
      <td style="text-align:left">
        <p>All</p>
        <p>CustomerManufacturer</p>
        <p>Manufacturer</p>
      </td>
      <td style="text-align:left">All</td>
    </tr>
    <tr>
      <td style="text-align:left">VatNumberMandatoryIfIsOrganization</td>
      <td style="text-align:left">La Partita IVA è obbligatoria se il cliente è un'organizzazione</td>
      <td
      style="text-align:left">Boolean</td>
        <td style="text-align:left"></td>
        <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>