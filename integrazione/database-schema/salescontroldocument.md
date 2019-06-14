---
description: Controlli commerciali sui documenti di vendita
---

# SalesControlDocument

**Chiavi**

* _Id_
* SalesControlType, ChannelsEnabled, AccountId, SalesAgentId, DocumentTypeId, CurrencyId, SeasonId, TrademarkId, StartDate, EndDate, StartAmountRange, EndAmountRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndAmountRange | Fine Scaglione importo | dec |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](salescontroldocument.md#salescontroltype) | Tipo di controllo | enum |  |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](salescontroldocument.md#severitylevel) | Livello di serietà | enum |  |
| StartAmountRange | Inizio Scaglione importo | dec |  |
| StartDate | Data inizio validità | date |  |
| TrademarkId | Id del trademark | text | 50 |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |
## SalesControlType

* 0: None
* 1: Importo minimo
* 2: Sconto medio totale massimo
## SeverityLevel

* 0: Error
* 1: Warning

