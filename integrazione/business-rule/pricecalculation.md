# PriceCalculation

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
      <td style="text-align:left">Algorithm</td>
      <td style="text-align:left">Algoritmo per il calcolo dei prezzi</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">MinimumNumberOfQuantityRangesToActivateNotification</td>
      <td style="text-align:left">Numero minimo di scaglioni quantità necessari per attivare la gestione
        degli scaglioni (e non considerarli semplicemente come articoli di cui
        è richiesta una quantità minima)</td>
      <td style="text-align:left">Int32</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">PricePerQtyMultiplierMode</td>
      <td style="text-align:left">Modalità di applicazione del moltiplicatore prezzi</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Applicato sul totale del documento</p>
        <p>1 => Applicato sul prezzo unitario</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">RetailPricesIncludeVat</td>
      <td style="text-align:left">I prezzi retail includono l'IVA</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => No</p>
        <p>1 => Yes</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
    <tr>
      <td style="text-align:left">TotalAmountDecimalDigitsRounding</td>
      <td style="text-align:left">Numero di cifre decimali negli importi totali</td>
      <td style="text-align:left">Int32</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">2</td>
    </tr>
    <tr>
      <td style="text-align:left">UnitPriceDecimalDigitsRounding</td>
      <td style="text-align:left">Numero di cifre decimali nei prezzi unitari</td>
      <td style="text-align:left">Int32</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">5</td>
    </tr>
    <tr>
      <td style="text-align:left">UnitPriceRoundingMode</td>
      <td style="text-align:left">Modalità di arrotondamento per i prezzi unitaru</td>
      <td style="text-align:left">Enum</td>
      <td style="text-align:left">
        <p>0 => Mathematical</p>
        <p>1 => RoundUp</p>
        <p>2 => RoundDown</p>
      </td>
      <td style="text-align:left">0</td>
    </tr>
  </tbody>
</table>