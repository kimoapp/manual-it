# Metadati sulle entità

In Kimo esistono entità di vario tipo:

* Entità in "sola lettura": importate dal Sistema Informativo \(Erp, Crm, ...\) e mai modificate in Kimo \(es. Documenti da Erp, anagrafica dei metodi di pagamento, condizioni di vendita, ...\).
* Entità creabili e/o modificabili nelle App di Kimo \(es. clienti, documenti di vendita, incassi, ...\).
* Entità di supporto creabili dalla [Console di Amministrazione](../introduzione/moduli/console-admin.md) di Kimo \(es. i tipi di documenti di vendita, i tipi di attività, i tipi di riassortimento, FreeLookup, ...\). Sono entità che gli utenti delle App di Kimo vedono in "sola lettura", non possono apportare modifiche ad esse, e non vengono esportate ai Sistemi Informativi.

I metadati in particolare si riferiscono alle entità creabili/modificabili dagli utenti attraverso le App di Kimo: definiscono per ciascun campo delle entità le regole di editing, come ad esempio la lunghezza massima per i campi di testo, l'obbligatorietà dell'inserimento di un determinato campo e così via.  
  
Se non vengono definiti i metadati per un'entità, i suoi campi risultano in sola lettura nelle App di Kimo.

### Metadati di entità

I metadati di entità definiscono i criteri di applicazione dei metadati di campo.

#### Contesto

Il contesto specifica uno o più ambiti applicativi in cui il metadato si applica.  
Il contesto è espresso nel formato Json array ma la sintassi è diversa per ciascuna entità.

es. Entità= Document indica che il metadato si applica a tutti i documenti \(Ordini, Offerte...\).   
Contesto =  \["Family=2", "Type=INITIAL"\] indica che il metadato si applica all'entità Documento di tipo Offerta o Preventivo o a Documenti con stato non ancora assegnato. 

<table>
  <thead>
    <tr>
      <th style="text-align:left">Entit&#xE0;</th>
      <th style="text-align:left">Sintassi del Contesto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Account</td>
      <td style="text-align:left">Supportato solo un contesto: [&quot;Prospect&quot;]</td>
    </tr>
    <tr>
      <td style="text-align:left">Prospect</td>
      <td style="text-align:left">Nessun contesto supportato.</td>
    </tr>
    <tr>
      <td style="text-align:left">Activity</td>
      <td style="text-align:left">Lista dei tipi di attivit&#xE0; espressi come codice del tipo di attivit&#xE0;
        es. [&quot;VISITA&quot;, &quot;FIERA&quot;]</td>
    </tr>
    <tr>
      <td style="text-align:left">RecurrentActivity</td>
      <td style="text-align:left">Nessun contesto supportato.</td>
    </tr>
    <tr>
      <td style="text-align:left">Contact</td>
      <td style="text-align:left">Nessun contesto supportato.</td>
    </tr>
    <tr>
      <td style="text-align:left">BudgetLine</td>
      <td style="text-align:left">Nessun contesto supportato</td>
    </tr>
    <tr>
      <td style="text-align:left">ReceivableInstallment</td>
      <td style="text-align:left">Nessun contesto supportato</td>
    </tr>
    <tr>
      <td style="text-align:left">Document</td>
      <td style="text-align:left">
        <p>Espresso nella forma [&quot;Type=&lt;valore&gt;&quot;, &quot;Family=&lt;valore&gt;&quot;]</p>
        <p>
          <br />Famiglia espressa come &quot;Family=2&quot; (1 per Ordini, 2 per Offerte)</p>
        <p>Id Document es. &quot;Type=DocumentType_1&quot;. Type pu&#xF2; inoltre
          assumere il valore INITIAL che indica il documento non ancora tipizzato.</p>
      </td>
    </tr>
  </tbody>
</table>#### Origine

L'attributo definisce l'applicazione del metadato in base all'origine del dato.  
Il parametro può assumere i seguenti valori: 

* 0 = Erp
* 1 = Creata su Mobile
* 2 = Modificata su Mobile
* 3 = Creata in KimoSuite

#### Padre

Se l'attributo Padre è non valorizzato, il metadato è considerarsi base per l'entità specificata.  
Se l'attributo ****Padre è valorizzato con "Base" il metadato estende il metadato base definito per dell'entità.  
  
Immaginiamo che per l'entità DocumentLine sia definito un metadato base con una serie di regole di editing che non prevedono la possibilità di alterare il prezzo.  
Se per la stessa entità voglio concedere, solo ad una certa categoria di utenti, la possibilità di modificare il prezzo, posso definire un nuovo metadato per l'entità DocumentLine che referenzia il metadato base e che concede l'autorizzazione alla lista di utenti desiderati.  
In questo modo è possibile gestire in modo centralizzato le regole di editing di una certa entità, ed estenderle se necessario ad una specifica categoria di utilizzatori, operando semplicemente per aggiunta.

#### Utenti/Agenti/Ruoli

Indica che i metadati specificati per l'entità si applicano solo ad una lista di utilizzatori \(nel formato Json array\):   
es. Utenti \["User\_6", "User\_10",...\], Agenti \["01", "02",...\], Ruoli \["Role\_03", "Role\_02",...\]  
Se l'attributo non è valorizzato le regole si applicano a tutti gli utilizzatori.

### Metadati di campo

Un metadato sul campo definisce se un campo può essere sottoposto ad aggiornamento e quali vincoli deve rispettare.   
Ad un Campo possono essere applicate una o più regole di editing.

| Attributo | Descrizione | Tipo |
| :--- | :--- | :--- |
| Editabile | Indica se il campo può essere modificato.  Può assumere i valori: 0=No 1=Si. | bool |
| Lunghezza Massima | Applicabile solo per i campi di tipo string. Indica la lunghezza massima che può assumere il valore. | int |
| Resettabile | Indica se deve essere visibile il tasto "Reset" che consente di azzerare il campo.  Può assumere i valori: 0=No 1=Si. | bool |
| Nullable | Indica se il campo può essere impostato a NULL.  Può assumere i valori: 0=No 1=Si. | bool |
| Obbligatorietà | Indica se la valorizzazione del campo è obbligatoria.  Può assumere i valori: 0=No 1=Si. | bool |
| Pattern Regex | Indica un'espressione regolare verificata in fase di salvataggio dell'entità. La sintassi da usare è quella del linguaggio C\#.  es. controllo sul numero di telefono \(^$\)\|\(^\[0-9\]{1,14}$\) | string |

 

