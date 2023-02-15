# Impostazioni di sistema

Le Impostazioni di sistema (Server System Settings) definiscono alcuni parametri utilizzati dal server di Kimo per determinare il comportamento di alcune funzionalità.

![](<../.gitbook/assets/tempsnip (1).png>)

![](<../.gitbook/assets/image (31).png>)

&#x20;Di seguito un elenco dettagliato delle impostazioni di sistema.&#x20;

### Impo~~s~~tazioni Web

| Chiave                     | Descrizione                                                                                                                                                                                  | Tipo   |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| <p></p><p>Web\BaseUrl </p> | <p></p><p>Indirizzo base del server (es. https://kimo.mycompany.com), utilizzato ad esempio per inserire dei link riferiti a Kimo nelle mail (es. mail per l'attivazione degli  utenti).</p> | string |

### Impostazioni mail server

| Chiave                 | Descrizione                                                                                                                                                                                | Tipo   |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| MailServer\SmtpServer  | Indirizzo del server SMTP utilizzato per l'invio delle email.                                                                                                                              | string |
| MailServer\Port        | <p>Porta del server SMTP utilizzato per l'invio delle email. <br>La porta di default di solito è la 25. <br>Nel caso di utilizzo del protocollo SSL la porta usata di solito è la 465.</p> | int    |
| MailServer\EnablSsl    | <p>Opzione che indica l'utilizzo del protocollo SSL. <br>Può assumere i valori: 0=No 1=Si</p>                                                                                              | bool   |
| MailServer\Username    | Nome utente da usare per l'autenticazione al server SMTP.                                                                                                                                  | string |
| MailServer\Password    | Password da usare per l'autenticazione al server SMTP.                                                                                                                                     | string |

### Impo~~s~~tazioni NotificationCenter (invio mail di notifica)

| Chiave                             | Descrizione                                                                                                                                                                | Tipo   |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| NotificationCenter\SenderAddress   | Indirizzo di posta elettronica del mittente delle email inviate da Kimo.                                                                                                   | string |
| NotificationCenter\SenderName      | Nome del mittente usato nelle email inviate da Kimo.                                                                                                                       | string |
| NotificationCenter\InfoRecipients  | Elenco degli indirizzi di posta elettronica a cui Kimo invia un'email di notifica: es. "Importazione avvenuta con successo".                                               | string |
| NotificationCenter\ErrorRecipients | Elenco degli indirizzi di posta elettronica a cui Kimo invia un'email in caso di errore o allerta es es. "Importazione fallita", "Esportazione fallita", "Errore interno". | string |

### Impo~~s~~tazioni User

| Chiave                        | Descrizione                                                                                                                                      | Tipo   |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| User\ActivationMailSubject    | <p>Oggetto della mail di attivazione degli utenti</p><p>Valore di default: "Attivazione utente Kimo / Kimo user activation"</p>                  | string |
| User\ActivationMailTitle      | <p>Titolo usato all'interno della mail di attivazione degli utenti</p><p>Valore di default: "Attivazione utente Kimo / Kimo user activation"</p> | string |
| User\ResetPasswordMailSubject | <p>Oggetto della mail di reset della password</p><p>Valore di default: "Ripristino password Kimo / Kimo password reset"</p>                      | string |
| User\ResetPasswordMailTitle   | <p>Titolo usato all'interno della mail di reset della password</p><p>Valore di default: "Ripristino password Kimo / Kimo password reset"</p>     | string |

### Impo~~s~~tazioni Thumbnail

| Chiave             | Descrizione                                                                                      | Tipo |
| ------------------ | ------------------------------------------------------------------------------------------------ | ---- |
| Thumbnail\ItemSize | Dimensione in pixel della thumbnail generata per le immagini degli articoli (di forma quadrata). | int  |

### Impo~~s~~tazioni **ItemsImage**

| Chiave              | Descrizione                                                                                                                                                             | Tipo |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| ItemsImages\MaxSize | <p>Dimensione massima in pixel che può assumere una immagine importata da Kimo (di forma quadrata).<br>Le immagini che superano tale soglia vengono ridimensionate.</p> | int  |

### Impostazioni Operations

| Chiave                   | Descrizione     | Tipo   |
| ------------------------ | --------------- | ------ |
| Operations\SemaphoreName | Non documentata | string |

### Impo~~s~~tazioni **Instance**

| Chiave      | Descrizione     | Tipo            |
| ----------- | --------------- | --------------- |
| Instance\Id | Non documentata | Non documentato |

### Impo~~s~~tazioni **Import**

| Chiave            | Descrizione                                                                                                                                                               | Tipo   |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| Import\CustomTask | Percorso di un eventuale script "custom" da eseguire. Per maggiori informazioni [Task personalizzati import/export](../integrazione/task-personalizzati-import-export.md) | string |

### Impo~~s~~tazioni **Firebase**

| Chiave                | Descrizione                                                    | Tipo   |
| --------------------- | -------------------------------------------------------------- | ------ |
| Firebase\AdminSdkB2a  | Non documentato                                                | string |
| Firebase\AdminSdkB2b  | Parametri di configurazione del Project FireBase dell'App B2B. | string |
| Firebase\ProjectIdB2a | Non documentato                                                | string |
| Firebase\ProjectIdB2b | ProjectId Firebase che identifica l'App B2B                    | string |

### Impo~~s~~tazioni **FileTypeId**

| Chiave                        | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Tipo   |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| \<FileTypeId>\SourceDirectory | <p>Famiglia di parametri per la definizione di cartelle. <br>&#x3C;FileTypeId> può assumere i seguenti valori:  </p><ul><li>ItemsImages: percorso immagini articoli</li><li>ItemsThumbnails: percorso miniature immagini articoli.</li><li>UserDocuments: percorso documenti utente.</li><li>CompanyDocuments: percorso documenti aziendali.</li><li>B2bCompanyDocuments: NON DOCUMENTATO</li><li>CompanyNews: NON DOCUMENTATO </li><li>Resources: NON DOCUMENTATO</li><li>ItemsAttachments: percorso schede articoli</li><li>PdfCatalog: percorso catalogo Pdf</li><li>PromotionsImages: percorso immagini articoli</li></ul> | string |
.