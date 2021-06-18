# DocumentNotification

| Valore | Descrizione |
| :--- | :--- |
| [**OnConfirmedCartSendMailToSalesAgents**](documentnotification.md#onconfirmedcartsendmailtosalesagents) | Se abilitato, alla conferma del documento viene automaticamente inviata la mail all'indirizzo degli agenti associati al cliente |
| [**OnConfirmedDocumentTypes**](documentnotification.md#onconfirmeddocumenttypes) | Tipi di documento per cui deve essere notificata la conferma |
| [**OnConfirmedMailBccRecipients**](documentnotification.md#onconfirmedmailbccrecipients) | Indirizzi a cui inviare in Bcc la mail di conferma ordine ogni volta che un utente conferma un documento |
| [**OnConfirmedMailBodyTemplate**](documentnotification.md#onconfirmedmailbodytemplate) | Template del corpo della mail di conferma documento |
| [**OnConfirmedMailRecipients**](documentnotification.md#onconfirmedmailrecipients) | Indirizzi a cui inviare la mail di conferma ogni volta che un utente conferma un documento |
| [**OnConfirmedMailSubjectTemplate**](documentnotification.md#onconfirmedmailsubjecttemplate) | Soggetto della mail di conferma documento |
| [**OnConfirmedReportType**](documentnotification.md#onconfirmedreporttype) | Tipo di report con cui generare l'allegato per la mail di conferma documento |
| [**OnConfirmedSendMailToCreator**](documentnotification.md#onconfirmedsendmailtocreator) | Se abilitato, alla conferma del documento viene automaticamente inviata la mail all'indirizzo dell'utente che ha creato il documento |
| [**OnConfirmedSendMailToCreatorRecipientMails**](documentnotification.md#onconfirmedsendmailtocreatorrecipientmails) | Se abilitato, le mail di conferma documento vengono inviate agli indirizzi aggiuntivi specificati per l'utente |
| [**SendOnConfirmed**](documentnotification.md#sendonconfirmed) | Indica se notificare la conferma di un documento |

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
* UserFullname
* UserMail
* WarehouseDescription
* WarehouseId

## OnConfirmedReportType

**Tipo:** String

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

## SendOnConfirmed

**Tipo:** Boolean

