# Stati Erp

Una lista di Stati Erp è un elenco di coppie di valori: codice, descrizione in cui ciascuna coppia identifica uno stato.  
Ciascun stato Erp ha un attributo "Tipo Stato" nella forma &lt;Entity&gt;&lt;Index&gt; che identifica l'Entity di riferimento ed il campo rispettivo Es. Item.ErpStatus1.  
Data un' Entity con uno dei campi ErpStatus&lt;Index&gt; valorizzato, se per ciascun valore del campo ErpStatus&lt;Index&gt;, non è possibile determinare il valore corrispondente in Stati Erp, la fase di Caricamento si interrompe con un errore.  
Per ciascun stato Erp è possibile inoltre definire: lo stile \(in formato CSS\) e un codice che identifica l'icona da visualizzare \(supporto a Font Awesome\). 

Es. Disponibilità Item

<table>
  <thead>
    <tr>
      <th style="text-align:left">Tipo Stato</th>
      <th style="text-align:left">Codice</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Codice Icona</th>
      <th style="text-align:left">Icona</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Item1</td>
      <td style="text-align:left">Rosso</td>
      <td style="text-align:left">Non disponibile</td>
      <td style="text-align:left">\uf165</td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="../.gitbook/assets/thumbsdown.PNG" alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Item1</td>
      <td style="text-align:left">Giallo</td>
      <td style="text-align:left">In arrivo</td>
      <td style="text-align:left">\uf107</td>
      <td style="text-align:left">
        <img src="../.gitbook/assets/clock.PNG" alt/>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Item1</td>
      <td style="text-align:left">Verde</td>
      <td style="text-align:left">Disponibile</td>
      <td style="text-align:left">\uf164</td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="../.gitbook/assets/thumbsup.PNG" alt/>
        </p>
      </td>
    </tr>
  </tbody>
</table>