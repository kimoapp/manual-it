# DocumentNotification

| Valore| Descrizione |
| :--- | :--- |
| [**OnConfirmedDocumentTypes**](documentnotification.md#onconfirmeddocumenttypes) |  |
| [**OnConfirmedMailBccRecipients**](documentnotification.md#onconfirmedmailbccrecipients) |  |
| [**OnConfirmedMailBodyTemplate**](documentnotification.md#onconfirmedmailbodytemplate) |  |
| [**OnConfirmedMailRecipients**](documentnotification.md#onconfirmedmailrecipients) |  |
| [**OnConfirmedMailSubjectTemplate**](documentnotification.md#onconfirmedmailsubjecttemplate) |  |
| [**OnConfirmedReportType**](documentnotification.md#onconfirmedreporttype) |  |
| [**OnConfirmedSendMailToCreator**](documentnotification.md#onconfirmedsendmailtocreator) |  |
| [**OnConfirmedSendMailToCreatorRecipientMails**](documentnotification.md#onconfirmedsendmailtocreatorrecipientmails) |  |
| [**SendOnConfirmed**](documentnotification.md#sendonconfirmed) |  |

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
* ShipmentSiteName

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
* ShipmentSiteName

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



