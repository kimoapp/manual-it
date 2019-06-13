# AccountAccountingInfo
Scheda contabile di un account

<br>
**Chiavi**
- *Id*
- AccountId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| CreditLimitGrantedAmount | Importo fido concesso | dec |  |
| CreditLimitOverAmount | Fuori fido | dec |  |
| CreditLimitResidualAmount | Importo fido residuo | dec |  |
| CreditLimitTemporaryAmount |  | dec |  |
| CreditLimitTemporaryAmountExpiryDate |  | date |  |
| CreditLimitUsedAmount | Importo fido utilizzato | dec |  |
| CurrencyId | Id della valuta | text | 50 |
| CustomerBalanceAmount | Saldo contabile | dec |  |
| ExposureAmount | Esposizione | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeDecimal4 | Campo decimale libero | dec |  |
| FreeDecimal5 | Campo decimale libero | dec |  |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id | text | 50 |
| InvoicesAmount | Importo anno corrente | dec |  |
| InvoicesNotRecordedAmount | Importo Bolle non fatturate | dec |  |
| InvoicesPastAmount | Importo anno precedente | dec |  |
| LastUpdateDate | Data ultimo aggiornamento | date |  |
| Notes | Note | text | text |
| SalesOrdersDeliveredAmount | Totale consegnati | dec |  |
| SalesOrdersNotShippedAmount | Totale non consegnati | dec |  |
| SalesOrdersWithExpiredShipmentTermsAmount | Totale con data di consegna scaduta | dec |  |
| SalesOrdersWithExpiringShipmentTermsAmount | Totale con data di consegna in scadenza | dec |  |
| UnpaidsAmount | Importo insoluti | dec |  |
| UnpaidsNumber | Numero insoluti anno corrente | int |  |
| UnpaidsPastNumber | Numero insoluti anno precedente | int |  |

