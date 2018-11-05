# ItemAvailability

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
      <td style="text-align:left">FilterMode</td>
      <td style="text-align:left">Modalità di filtro delle disponibilità durante la preparazione dati per
        gli agenti</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Per magazzino dell'utente/agente</p>
        <p>1 => Nessun filtro</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">GlobalAvailabilityMode</td>
      <td style="text-align:left">Modalità di calcolo della disponibilità globale</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'</p>
        <p>1 => Calcolata dalle disponibilità nei magazzini</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">QtyField</td>
      <td style="text-align:left">Campo da considerare per verificare la quantità disponibile</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => SalesQty</p>
        <p>1 => NumberOfPacks</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
  </tbody>
</table>