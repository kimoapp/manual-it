# DocumentNotification

| Valore | Descrizione |
| :--- | :--- |
| [**OnConfirmedDocumentTypes**](documentnotification.md#onconfirmeddocumenttypes)\*\* |  |
| [**OnConfirmedMailBccRecipients**](documentnotification.md#onconfirmedmailbccrecipients)\*\* |  |
| [**OnConfirmedMailBodyTemplate**](documentnotification.md#onconfirmedmailbodytemplate)\*\* |  |
| [**OnConfirmedMailRecipients**](documentnotification.md#onconfirmedmailrecipients)\*\* |  |
| [**OnConfirmedMailSubjectTemplate**](documentnotification.md#onconfirmedmailsubjecttemplate)\*\* |  |
| [**OnConfirmedReportType**](documentnotification.md#onconfirmedreporttype)\*\* |  |
| [**OnConfirmedSendMailToCreator**](documentnotification.md#onconfirmedsendmailtocreator)\*\* |  |
| [**OnConfirmedSendMailToCreatorRecipientMails**](documentnotification.md#onconfirmedsendmailtocreatorrecipientmails)\*\* |  |
| [**SendOnConfirmed**](documentnotification.md#sendonconfirmed)\*\* |  |

## $h2 OnConfirmedDocumentTypes

**Tipo:** Valori separati da pipe

## $h2 OnConfirmedMailBccRecipients

**Tipo:** String

## $h2 OnConfirmedMailBodyTemplate

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
* ShipmentSiteName

## $h2 OnConfirmedMailRecipients

**Tipo:** String

## $h2 OnConfirmedMailSubjectTemplate

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
* ShipmentSiteName

## $h2 OnConfirmedReportType

**Tipo:** String

## $h2 OnConfirmedSendMailToCreator

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## $h2 OnConfirmedSendMailToCreatorRecipientMails

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; None
* 1 =&gt; To
* 2 =&gt; Cc
* 3 =&gt; Bcc

## $h2 SendOnConfirmed

**Tipo:** Boolean

