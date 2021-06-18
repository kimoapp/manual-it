# Stati Erp

Una lista di stati erp è un elenco di coppie di valori: codice, descrizione in cui ciascuna coppia identifica uno stato.  
Ciascun stato erp ha un attributo "Tipo Stato" nella forma &lt;Entity&gt;&lt;Index&gt; che identifica l'Entity di riferimento ed il campo rispettivo Es. Item.ErpStatus1.  
Data un' entità con uno dei campi ErpStatus&lt;Index&gt; valorizzato, se per ciascun valore del campo ErpStatus&lt;Index&gt;, non è possibile determinare il valore corrispondente in stati erp, la fase di caricamento si interrompe con un errore.  
Per ciascun stato erp è possibile inoltre definire: lo stile \(in formato CSS\) e un codice che identifica l'icona da visualizzare \(supporto a Font Awesome\). 

![](../.gitbook/assets/statoerp.PNG)

Es. Disponibilità Item

<table>
  <thead>
    <tr>
      <th style="text-align:left">Tipo Stato</th>
      <th style="text-align:left">Value Id</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Icona</th>
      <th style="text-align:left">Anteprima</th>
      <th style="text-align:left">Stile</th>
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
      <td style="text-align:left">color: #FF0000; font-family: FontAwesomeRegular; font-size: 20;</td>
    </tr>
    <tr>
      <td style="text-align:left">Item1</td>
      <td style="text-align:left">Giallo</td>
      <td style="text-align:left">In arrivo</td>
      <td style="text-align:left">\uf107</td>
      <td style="text-align:left">
        <img src="../.gitbook/assets/clock.PNG" alt/>
      </td>
      <td style="text-align:left">color: #FFD300; font-family: FontAwesomeRegular; font-size: 20;</td>
    </tr>
    <tr>
      <td style="text-align:left">Item1</td>
      <td style="text-align:left">Verde</td>
      <td style="text-align:left">Disponibile</td>
      <td style="text-align:left">\uf164</td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="../.gitbook/assets/thumbsup (1) (1).PNG" alt/>
        </p>
      </td>
      <td style="text-align:left">color: #009933; font-family: FontAwesomeRegular; font-size: 20;</td>
    </tr>
  </tbody>
</table>

