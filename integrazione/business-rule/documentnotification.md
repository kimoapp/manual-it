# DocumentNotification
OnConfirmedDocumentTypes 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Valori separati da pipe <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

OnConfirmedMailBccRecipients 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** String <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

OnConfirmedMailBodyTemplate 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Template <br>
**Valore di default:** ${DocumentType} '${DocumentNumber}' confermato! <br>
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
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** String <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

OnConfirmedMailSubjectTemplate 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Template <br>
**Valore di default:** ${DocumentType} '${DocumentNumber}' confermato! <br>
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
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** String <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

OnConfirmedSendMailToCreator 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Boolean <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

SendOnConfirmed 
----
**Descrizione:** $businessRule.Description <br>
**Tipo:** Boolean <br>
**Valore di default:** $businessRule.DefaultValue <br>
**Valori:**

