# Impostazioni di sistema

Le Impostazioni di sistema \(Server System Settings\) definiscono alcuni parametri utilizzati dal server di Kimo per determinare il comportamento di alcune funzionalità.

![](../.gitbook/assets/tempsnip%20%281%29.png)

![](../.gitbook/assets/image%20%2826%29.png)

 Di seguito un elenco dettagliato delle impostazioni di sistema. 

### Impo~~s~~tazioni Web

<table>
  <thead>
    <tr>
      <th style="text-align:left">Chiave</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Tipo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>Web\BaseUrl</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>Indirizzo base del server (es. https://kimo.mycompany.com), utilizzato
          ad esempio per inserire dei link riferiti a Kimo nelle mail (es. mail per
          l&apos;attivazione degli utenti).</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
  </tbody>
</table>### Impostazioni mail server

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| MailServer\SmtpServer  | Indirizzo del server SMTP utilizzato per l'invio delle email. | string |
| MailServer\Port | Porta del server SMTP utilizzato per l'invio delle email.  La porta di default di solito è la 25.  Nel caso di utilizzo del protocollo SSL la porta usata di solito è la 465. | int |
| MailServer\EnablSsl | Opzione che indica l'utilizzo del protocollo SSL.  Può assumere i valori: 0=No 1=Si | bool |
| MailServer\Username | Nome utente da usare per l'autenticazione al server SMTP. | string |
| MailServer\Password | Password da usare per l'autenticazione al server SMTP. | string |

### Impo~~s~~tazioni NotificationCenter \(invio mail di notifica\)

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| NotificationCenter\SenderAddress | Indirizzo di posta elettronica del mittente delle email inviate da Kimo. | string |
| NotificationCenter\SenderName | Nome del mittente usato nelle email inviate da Kimo. | string |
| NotificationCenter\InfoRecipients  | Elenco degli indirizzi di posta elettronica a cui Kimo invia un'email di notifica: es. "Importazione avvenuta con successo". | string |
| NotificationCenter\ErrorRecipients | Elenco degli indirizzi di posta elettronica a cui Kimo invia un'email in caso di errore o allerta es es. "Importazione fallita", "Esportazione fallita", "Errore interno". | string |

### Impo~~s~~tazioni User

<table>
  <thead>
    <tr>
      <th style="text-align:left">Chiave</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Tipo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">User\ActivationMailSubject</td>
      <td style="text-align:left">
        <p>Oggetto della mail di attivazione degli utenti</p>
        <p>Valore di default: &quot;Attivazione utente Kimo / Kimo user activation&quot;</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
    <tr>
      <td style="text-align:left">User\ActivationMailTitle</td>
      <td style="text-align:left">
        <p>Titolo usato all&apos;interno della mail di attivazione degli utenti</p>
        <p>Valore di default: &quot;Attivazione utente Kimo / Kimo user activation&quot;</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
    <tr>
      <td style="text-align:left">User\ResetPasswordMailSubject</td>
      <td style="text-align:left">
        <p>Oggetto della mail di reset della password</p>
        <p>Valore di default: &quot;Ripristino password Kimo / Kimo password reset&quot;</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
    <tr>
      <td style="text-align:left">User\ResetPasswordMailTitle</td>
      <td style="text-align:left">
        <p>Titolo usato all&apos;interno della mail di reset della password</p>
        <p>Valore di default: &quot;Ripristino password Kimo / Kimo password reset&quot;</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
  </tbody>
</table>### Impo~~s~~tazioni Thumbnail

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Thumbnail\ItemSize | Dimensione in pixel della thumbnail generata per le immagini degli articoli \(di forma quadrata\). | int |

### Impo~~s~~tazioni **ItemsImage**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| ItemsImages\MaxSize | Dimensione massima in pixel che può assumere una immagine importata da Kimo \(di forma quadrata\). Le immagini che superano tale soglia vengono ridimensionate. | int |

### Impostazioni Operations

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Operations\SemaphoreName | Non documentata | string |

### Impo~~s~~tazioni **Instance**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Instance\Id | Non documentata | Non documentato |

### Impo~~s~~tazioni **Import**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Import\CustomTask | Percorso di un eventuale script "custom" da eseguire. Per maggiori informazioni [Task personalizzati import/export](../integrazione/task-personalizzati-import-export.md) | string |

### Impo~~s~~tazioni **Firebase**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Firebase\AdminSdkB2a | Non documentato | string |
| Firebase\AdminSdkB2b | Parametri di configurazione del Project FireBase dell'App B2B. | string |
| Firebase\ProjectIdB2a | Non documentato | string |
| Firebase\ProjectIdB2b | ProjectId Firebase che identifica l'App B2B | string |

### Impo~~s~~tazioni **FileTypeId**

<table>
  <thead>
    <tr>
      <th style="text-align:left">Chiave</th>
      <th style="text-align:left">Descrizione</th>
      <th style="text-align:left">Tipo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&lt;FileTypeId&gt;\SourceDirectory</td>
      <td style="text-align:left">
        <p>Famiglia di parametri per la definizione di cartelle.
          <br />&lt;FileTypeId&gt; pu&#xF2; assumere i seguenti valori:</p>
        <ul>
          <li>ItemsImages: percorso immagini articoli</li>
          <li>ItemsThumbnails: percorso miniature immagini articoli.</li>
          <li>UserDocuments: percorso documenti utente.</li>
          <li>CompanyDocuments: percorso documenti aziendali.</li>
          <li>B2bCompanyDocuments: NON DOCUMENTATO</li>
          <li>CompanyNews: NON DOCUMENTATO</li>
          <li>Resources: NON DOCUMENTATO</li>
          <li>ItemsAttachments: percorso schede articoli</li>
          <li>PdfCatalog: percorso catalogo Pdf</li>
        </ul>
      </td>
      <td style="text-align:left">string</td>
    </tr>
  </tbody>
</table>