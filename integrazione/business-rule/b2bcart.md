# B2b\Cart

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
      <td style="text-align:left">CartFromReassortmentNameTemplate</td>
      <td style="text-align:left">Template per il nome del carrello creato dal riassortimento</td>
      <td style="text-align:left">Template</td>
      <td style="text-align:left">
        <p>CreationDate</p>
        <p>ReassortmentType.Description</p>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">CreditLimitCheck</td>
      <td style="text-align:left">Tipo di controllo sul fido al checkout</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Nessun controllo</p>
        <p>1 => Importo totale (con IVA e spese accessorie incluse)</p>
        <p>2 => Totale merce (IVA esclusa)</p>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">MaxQtyValidationType</td>
      <td style="text-align:left">Tipo di validazione della quantità</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Nessun controllo</p>
        <p>1 => In confronto alla disponibilità</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">ReassortmentTypeAsConstraintIsMandatory</td>
      <td style="text-align:left">Tipo Riassortimento come vincolo obbligatorio</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">ShipmentSiteIsMandatory</td>
      <td style="text-align:left">Destinazione merci obbligatoria</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">ValidatePricesObsolescence</td>
      <td style="text-align:left">Abilita la validazione dei prezzi al checkout</td>
      <td style="text-align:left">Boolean</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">True</td>
    </tr>
  </tbody>
</table>