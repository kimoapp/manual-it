# Impostazioni di sistema

Le Impostazioni di Sistema \(Server System Settings\) definiscono alcuni parametri utilizzati dal server di Kimo per determinare il comportamento di alcune funzionalità.

![](../.gitbook/assets/tempsnip%20%281%29.png)

![](../.gitbook/assets/image%20%2826%29.png)

 È possibile consultarne un elenco più dettagliato nella seguente sezione: 

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
        <p>MailServer\SmtpServer</p>
      </td>
      <td style="text-align:left">Indirizzo server SMTP</td>
      <td style="text-align:left">string</td>
    </tr>
    <tr>
      <td style="text-align:left">MailServer\Port</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">int</td>
    </tr>
    <tr>
      <td style="text-align:left">MailServer\EnablSsl</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">bool</td>
    </tr>
    <tr>
      <td style="text-align:left">MailServer\Username</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">string</td>
    </tr>
    <tr>
      <td style="text-align:left">MailServer\Password</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">string</td>
    </tr>
  </tbody>
</table>### Impo~~s~~tazioni NotificationCenter \(invio mail di notifica\)

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| NotificationCenter\SenderAddress |  | string |
| NotificationCenter\SenderName |  | string |
| NotificationCenter\InfoRecipients  |  | string |
| NotificationCenter\ErrorRecipients |  | string |

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
| ItemsImages\MaxSize |  | int |

### Impostazioni Operations

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Operations\SemaphoreName |  | string |

### Impo~~s~~tazioni **Instance**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Instance\Id |  | string |

### Impo~~s~~tazioni **Import**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Import\CustomTask | Percorso di un eventuale script "custom" da eseguire. Per maggiori informazioni [Task personalizzati import/export](../integrazione/task-personalizzati-import-export.md) | string |

### Impo~~s~~tazioni **Firebase**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Firebase\AdminSdkB2a |  | string |
| Firebase\AdminSdkB2b |  | string |
| Firebase\ProjectIdB2a |  | string |
| Firebase\ProjectIdB2b |  | string |

### Impo~~s~~tazioni **FileTypeId**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| FileTypeId\SourceDirectory |  | string |

