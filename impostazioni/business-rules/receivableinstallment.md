# ReceivableInstallment

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](receivableinstallment.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**AllowMultiplePaymentsForInstallment**](receivableinstallment.md#allowmultiplepaymentsforinstallment) | Consente di registrare più pagamenti per una stessa partita |
| [**AllowPaidAmountGreaterThanExpected**](receivableinstallment.md#allowpaidamountgreaterthanexpected) | Permette all'agente di incassare un importo maggiore di quello previsto dalla partita |
| [**CustomerScheduledPaymentsStates**](receivableinstallment.md#customerscheduledpaymentsstates) | Stati pagamento per cui mostrare gli elementi nello scadenzario del cliente |
| [**KeywordSearchFields**](receivableinstallment.md#keywordsearchfields) | Campi per la ricerca testuale |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** SearchType\|Timeframe\|ExpirationStatus  
**Valori:**

* ExpirationStatus
* SearchType
* Timeframe

## AllowMultiplePaymentsForInstallment

**Tipo:** Boolean

## AllowPaidAmountGreaterThanExpected

**Tipo:** Boolean

## CustomerScheduledPaymentsStates

**Tipo:** Valori separati da pipe  
**Valore di default:** 0\|1  
**Valori:**

* 0 =&gt; ToPay
* 1 =&gt; Paid
* 2 =&gt; Unpaid
* 3 =&gt; PaidOnKimo

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** ReceivableInstallment.CustomerCode\|ReceivableInstallment.CustomerName\|ReceivableInstallment.CustomerName2\|ReceivableInstallment.ReceivableId\|ReceivableInstallment.ReceivableNumber  
**Valori:**

* ReceivableId
* ReceivableNumber
