# DocumentNotification

| Valore | Descrizione |
| :--- | :--- |
| [**OnCartSentForApprovalRequestMailBodyTemplate**](documentnotification.md#oncartsentforapprovalrequestmailbodytemplate) | Template del corpo della mail di notifica carrello inviato per approvazione |
| [**OnCartSentForApprovalRequestMailSubjectTemplate**](documentnotification.md#oncartsentforapprovalrequestmailsubjecttemplate) | Soggetto della mail di notifica carrello inviato per approvazione |
| [**OnCartSentForApprovalRequestReportType**](documentnotification.md#oncartsentforapprovalrequestreporttype) | Tipo di report con cui generare l'allegato per la mail di notifica carrello inviato per approvazione |
| [**OnConfirmedCartSendMailToOriginalCreator**](documentnotification.md#onconfirmedcartsendmailtooriginalcreator) | Indica se notificare la conferma del carrello all'utente che lo aveve originariamente creato |
| [**OnConfirmedCartSendMailToReferenceSalesAgent**](documentnotification.md#onconfirmedcartsendmailtoreferencesalesagent) | Se abilitato, alla conferma del carrello viene automaticamente inviata la mail all'indirizzo degll'agente di riferimento del cliente |
| [**OnConfirmedCartSendMailToSalesAgents**](documentnotification.md#onconfirmedcartsendmailtosalesagents) | Se abilitato, alla conferma del carrello viene automaticamente inviata la mail all'indirizzo degli agenti associati al cliente |
| [**OnConfirmedDocumentTypes**](documentnotification.md#onconfirmeddocumenttypes) | Tipi di documento per cui deve essere notificata la conferma |
| [**OnConfirmedMailBccRecipients**](documentnotification.md#onconfirmedmailbccrecipients) | Indirizzi a cui inviare in Bcc la mail di conferma ordine ogni volta che un utente conferma un documento |
| [**OnConfirmedMailBodyTemplate**](documentnotification.md#onconfirmedmailbodytemplate) | Template del corpo della mail di conferma documento |
| [**OnConfirmedMailRecipients**](documentnotification.md#onconfirmedmailrecipients) | Indirizzi a cui inviare la mail di conferma ogni volta che un utente conferma un documento |
| [**OnConfirmedMailSubjectTemplate**](documentnotification.md#onconfirmedmailsubjecttemplate) | Soggetto della mail di conferma documento |
| [**OnConfirmedReportType**](documentnotification.md#onconfirmedreporttype) | Tipo di report con cui generare l'allegato per la mail di conferma documento |
| [**OnConfirmedSendMailToAccount**](documentnotification.md#onconfirmedsendmailtoaccount) | Se abilitato, alla conferma del documento viene automaticamente inviata la mail all'indirizzo del cliente |
| [**OnConfirmedSendMailToCreator**](documentnotification.md#onconfirmedsendmailtocreator) | Se abilitato, alla conferma del documento viene automaticamente inviata la mail all'indirizzo dell'utente che ha creato il documento |
| [**OnConfirmedSendMailToCreatorRecipientMails**](documentnotification.md#onconfirmedsendmailtocreatorrecipientmails) | Se abilitato, le mail di conferma documento vengono inviate agli indirizzi aggiuntivi specificati per l'utente |
| [**SendOnCartApprovalRequest**](documentnotification.md#sendoncartapprovalrequest) | Indica se notificare la richiesta approvazione di un carrello |
| [**SendOnConfirmed**](documentnotification.md#sendonconfirmed) | Indica se notificare la conferma di un documento |
| [**ShouldSendCsvReportOnCartConfirmed**](documentnotification.md#shouldsendcsvreportoncartconfirmed) | Indica se necessario allegare il report Csv alla mail di conferma carrello |

## OnCartSentForApprovalRequestMailBodyTemplate

**Tipo:** String

## OnCartSentForApprovalRequestMailSubjectTemplate

**Tipo:** String

## OnCartSentForApprovalRequestReportType

**Tipo:** String

## OnConfirmedCartSendMailToOriginalCreator

**Tipo:** Boolean

## OnConfirmedCartSendMailToReferenceSalesAgent

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## OnConfirmedCartSendMailToSalesAgents

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## OnConfirmedDocumentTypes

**Tipo:** Valori separati da pipe

## OnConfirmedMailBccRecipients

**Tipo:** String

## OnConfirmedMailBodyTemplate

**Tipo:** Template  
**Valore di default:** ${DocumentType} '${DocumentNumber}' confermato!  
**Valori:**

* AccountCode
* AccountFreeText
* AccountName
* DocumentAmount
* DocumentAmountIncludingVat
* DocumentDate
* DocumentNumber
* DocumentReference
* DocumentType
* DocumentUrl
* ShipmentSiteCode
* ShipmentSiteFreeText
* ShipmentSiteId
* ShipmentSiteName
* TrademarkDescription
* TrademarkId
* UserFullname
* UserMail
* WarehouseDescription
* WarehouseId

## OnConfirmedMailRecipients

**Tipo:** String

## OnConfirmedMailSubjectTemplate

**Tipo:** Template  
**Valore di default:** ${DocumentType} '${DocumentNumber}' confermato!  
**Valori:**

* AccountCode
* AccountFreeText
* AccountName
* DocumentAmount
* DocumentAmountIncludingVat
* DocumentDate
* DocumentNumber
* DocumentReference
* DocumentType
* DocumentUrl
* ShipmentSiteCode
* ShipmentSiteFreeText
* ShipmentSiteId
* ShipmentSiteName
* TrademarkDescription
* TrademarkId
* UserFullname
* UserMail
* WarehouseDescription
* WarehouseId

## OnConfirmedReportType

**Tipo:** String

## OnConfirmedSendMailToAccount

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## OnConfirmedSendMailToCreator

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## OnConfirmedSendMailToCreatorRecipientMails

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## SendOnCartApprovalRequest

**Tipo:** Boolean

## SendOnConfirmed

**Tipo:** Boolean

## ShouldSendCsvReportOnCartConfirmed

**Tipo:** Boolean
