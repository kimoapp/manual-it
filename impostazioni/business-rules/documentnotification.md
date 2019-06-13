# DocumentNotification

| Valore| Descrizione |
| :--- | :--- |
| [**OnConfirmedDocumentTypes**](#onconfirmeddocumenttypes)** |  |
| [**OnConfirmedMailBccRecipients**](#onconfirmedmailbccrecipients)** |  |
| [**OnConfirmedMailBodyTemplate**](#onconfirmedmailbodytemplate)** |  |
| [**OnConfirmedMailRecipients**](#onconfirmedmailrecipients)** |  |
| [**OnConfirmedMailSubjectTemplate**](#onconfirmedmailsubjecttemplate)** |  |
| [**OnConfirmedReportType**](#onconfirmedreporttype)** |  |
| [**OnConfirmedSendMailToCreator**](#onconfirmedsendmailtocreator)** |  |
| [**OnConfirmedSendMailToCreatorRecipientMails**](#onconfirmedsendmailtocreatorrecipientmails)** |  |
| [**SendOnConfirmed**](#sendonconfirmed)** |  |

$h2 OnConfirmedDocumentTypes 
-----
**Tipo:** Valori separati da pipe	 

$h2 OnConfirmedMailBccRecipients 
-----
**Tipo:** String	 

$h2 OnConfirmedMailBodyTemplate 
-----
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

$h2 OnConfirmedMailRecipients 
-----
**Tipo:** String	 

$h2 OnConfirmedMailSubjectTemplate 
-----
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

$h2 OnConfirmedReportType 
-----
**Tipo:** String	 

$h2 OnConfirmedSendMailToCreator 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => None
* 1 => To
* 2 => Cc
* 3 => Bcc

$h2 OnConfirmedSendMailToCreatorRecipientMails 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => None
* 1 => To
* 2 => Cc
* 3 => Bcc

$h2 SendOnConfirmed 
-----
**Tipo:** Boolean

