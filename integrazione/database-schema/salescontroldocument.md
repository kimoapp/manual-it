---
description: Controlli commerciali sui documenti di vendita
---

# SalesControlDocument

**Chiavi**

* _Id_
* SalesControlType, ChannelsEnabled, AccountEncodingType, AccountEncodingKey, SalesAgentId, DocumentTypeId, CurrencyId, PromotionId, SeasonId, TrademarkId, StartDate, EndDate, StartAmountRange, EndAmountRange, StartQuantityRange, EndQuantityRange, UomType, UomId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](salescontroldocument.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndAmountRange | Fine Scaglione importo | dec |  |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| Id | Id | text | 50 |
| MaxDiscount1 | Sconti massimi per la testata | dec |  |
| MaxDiscount2 | Sconti massimi per la testata | dec |  |
| MaxDiscount3 | Sconti massimi per la testata | dec |  |
| MaxLineDiscount1 | Sconti massimi per le righe | dec |  |
| MaxLineDiscount2 | Sconti massimi per le righe | dec |  |
| MaxLineDiscount3 | Sconti massimi per le righe | dec |  |
| MaxLineDiscount4 | Sconti massimi per le righe | dec |  |
| MaxLineDiscount5 | Sconti massimi per le righe | dec |  |
| [MessageVerbosityLevel](salescontroldocument.md#messageverbositylevel) | Livello di verbosità dei messaggi per le validazioni fallite | enum |  |
| [MultipleQuantity](salescontroldocument.md#multiplequantity) | Quantità multipla | dec |  |
| PromotionId | Id della promozione | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](salescontroldocument.md#salescontroltype) | Tipo di controllo | enum |  |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](salescontroldocument.md#severitylevel) | Livello di serietà | enum |  |
| StartAmountRange | Inizio Scaglione importo | dec |  |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| TrademarkId | Id del trademark | text | 50 |
| UomId | Id dell'unità di misura \(di vendita o di imballo\) | text | 20 |
| [UomType](salescontroldocument.md#uomtype) | Tipo dell'unità di misura \(di vendita o di imballo\) | enum |  |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup

## MessageVerbosityLevel

* 0: Default
* 1: DoNotShowValue

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## SalesControlType

* 0: None
* 1: Importo minimo
* 2: Sconto medio totale massimo
* 3: Importo massimo omaggiabile per promozione
* 4: Sconto massimo di riga per quantità totale in documento
* 5: Punti disponibili nel borsellino

## SeverityLevel

* 0: Error
* 1: Warning

## UomType

* 0: SalesUom
* 1: PackUom
