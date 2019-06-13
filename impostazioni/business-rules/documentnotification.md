# DocumentNotification
| Valore| Descrizione |
| --- | --- |
| **[OnConfirmedDocumentTypes](#onconfirmeddocumenttypes)** |  |
| **[OnConfirmedMailBccRecipients](#onconfirmedmailbccrecipients)** |  |
| **[OnConfirmedMailBodyTemplate](#onconfirmedmailbodytemplate)** |  |
| **[OnConfirmedMailRecipients](#onconfirmedmailrecipients)** |  |
| **[OnConfirmedMailSubjectTemplate](#onconfirmedmailsubjecttemplate)** |  |
| **[OnConfirmedReportType](#onconfirmedreporttype)** |  |
| **[OnConfirmedSendMailToCreator](#onconfirmedsendmailtocreator)** |  |
| **[OnConfirmedSendMailToCreatorRecipientMails](#onconfirmedsendmailtocreatorrecipientmails)** |  |
| **[SendOnConfirmed](#sendonconfirmed)** |  |

OnConfirmedDocumentTypes 
-----
**Tipo:** Valori separati da pipe	 

OnConfirmedMailBccRecipients 
-----
**Tipo:** String	 

OnConfirmedMailBodyTemplate 
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

OnConfirmedMailRecipients 
-----
**Tipo:** String	 

OnConfirmedMailSubjectTemplate 
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

OnConfirmedReportType 
-----
**Tipo:** String	 

OnConfirmedSendMailToCreator 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => None
* 1 => To
* 2 => Cc
* 3 => Bcc

OnConfirmedSendMailToCreatorRecipientMails 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => None
* 1 => To
* 2 => Cc
* 3 => Bcc

SendOnConfirmed 
-----
**Tipo:** Boolean

