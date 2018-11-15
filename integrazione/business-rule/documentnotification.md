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
* AccountName
* DocumentAmount
* DocumentAmountIncludingVat
* DocumentDate
* DocumentNumber
* DocumentReference
* DocumentType
* DocumentUrl

OnConfirmedMailRecipients 
-----
**Tipo:** String	 

OnConfirmedMailSubjectTemplate 
-----
**Tipo:** Template	 
**Valore di default:** ${DocumentType} '${DocumentNumber}' confermato!	 
**Valori:**
* AccountCode
* AccountName
* DocumentAmount
* DocumentAmountIncludingVat
* DocumentDate
* DocumentNumber
* DocumentReference
* DocumentType
* DocumentUrl

OnConfirmedReportType 
-----
**Tipo:** String	 

OnConfirmedSendMailToCreator 
-----
**Tipo:** Boolean	 

SendOnConfirmed 
-----
**Tipo:** Boolean

