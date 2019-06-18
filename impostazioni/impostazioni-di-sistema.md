# Impostazioni di sistema

Le Impostazioni di Sistema \(Server System Settings\) definiscono alcuni parametri che servono al server  per l'utilizzo di alcune funzioni. È possibile consultarne un elenco più dettagliato nella seguente sezione: 

![](../.gitbook/assets/tempsnip%20%281%29.png)

![](../.gitbook/assets/image%20%2826%29.png)

### Impostazioni mail server

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
</table>### Impo~~s~~tazioni Web

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
        <p>Indirizzo del server</p>
      </td>
      <td style="text-align:left">string</td>
    </tr>
  </tbody>
</table>### Impo~~s~~tazioni User

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| User\ActivationMailSubject  | Default-&gt; Attivazione utente Kimo / Kimo user activation | string |
| User\ActivationMailTitle | Default -&gt; Attivazione utente Kimo / Kimo user activation | string |
| User\ResetPasswordMailSubject | Default -&gt; Ripristino password Kimo / Kimo password reset | string |
| User\ResetPasswordMailTitle | Default-&gt; Ripristino password Kimo / Kimo password reset | string |

### Impo~~s~~tazioni Thumbnail

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Thumbnail\ItemSize | Dimensione in pixel della thumbnail | int |

### Impo~~s~~tazioni Status

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Status\LastImportRequestTimeStamp |  | datetime |
| Status\LastImportStartTimeStamp  |  | datetime |
| Status\LastImportFinishTimeStamp |  | datetime |
| Status\LastExportRequestTimeStamp |  | datetime |
| Status\LastExportStartTimeStamp |  | datetime |
| Status\LastExportFinishTimeStamp |  | datetime |
| Status\BaseUrl | Default -&gt; [https://kimostorage.blob.core.windows.net/kimoversions](https://kimostorage.blob.core.windows.net/kimoversions) | string |

### Impo~~s~~tazioni Operations

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Operations\SemaphoreName |  | string |

### Impo~~s~~tazioni Operations

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| NotificationCenter\SenderAddress |  | string |
| NotificationCenter\SenderName |  | string |
| NotificationCenter\InfoRecipients  |  | string |
| NotificationCenter\ErrorRecipients |  | string |

### Impo~~s~~tazioni **ItemsImage**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| ItemsImages\MaxSize |  | int |

### Impo~~s~~tazioni **Instance**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Instance\Id |  | string |

### Impo~~s~~tazioni **Import**

| Chiave | Descrizione | Tipo |
| :--- | :--- | :--- |
| Import\CustomTask | Percorso dello script da eseguire. Per maggiori informazioni [Task personalizzati import/export](../integrazione/task-personalizzati-import-export.md) | string |

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

