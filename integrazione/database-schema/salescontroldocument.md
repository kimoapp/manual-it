---
description: Controlli commerciali sui documenti di vendita
---

# SalesControlDocument

**Chiavi**

* _Id_
* SalesControlType, ChannelsEnabled, AccountEncodingType, AccountEncodingKey, SalesAgentId, DocumentTypeId, CurrencyId, PromotionId, SeasonId, TrademarkId, StartDate, EndDate, StartAmountRange, EndAmountRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](salescontroldocument.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndAmountRange | Fine Scaglione importo | dec |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| [MessageVerbosityLevel](salescontroldocument.md#messageverbositylevel) | Livello di verbosità dei messaggi per le validazioni fallite | enum |  |
| PromotionId | Id della promozione | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](salescontroldocument.md#salescontroltype) | Tipo di controllo | enum |  |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](salescontroldocument.md#severitylevel) | Livello di serietà | enum |  |
| StartAmountRange | Inizio Scaglione importo | dec |  |
| StartDate | Data inizio validità | date |  |
| TrademarkId | Id del trademark | text | 50 |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup

## MessageVerbosityLevel

* 0: Default
* 1: DoNotShowValue

## SalesControlType

* 0: None
* 1: Importo minimo
* 2: Sconto medio totale massimo
* 3: Importo massimo omaggiabile per promozione

## SeverityLevel

* 0: Error
* 1: Warning
