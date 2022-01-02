---
description: Righe dei controlli commerciali sui documenti di vendita
---

# SalesControlLine

**Chiavi**

* _Id_
* SalesControlId, AccountEncodingType, AccountEncodingKey, ItemEncodingType, ItemEncodingKey, VariableItemId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, UomId, SalesAgentId, DocumentTypeId, SeasonId, TrademarkId, CurrencyId, PromotionId, StartDate, EndDate, StartQuantityRange, EndQuantityRange, StartAmountRange, EndAmountRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](salescontrolline.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndAmountRange | Fine Scaglione importo | dec |  |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| Id | Id | text | 50 |
| ItemEncodingKey | Chiave identificativa per gli articoli \(codice, gruppo, ...\) | text | 50 |
| [ItemEncodingType](salescontrolline.md#itemencodingtype) | Tipo della chiave identificativa per gli articoli | enum |  |
| MaxDiscount1 | Sconti massimi | dec |  |
| MaxDiscount2 | Sconti massimi | dec |  |
| MaxDiscount3 | Sconti massimi | dec |  |
| MaxDiscount4 | Sconti massimi | dec |  |
| MaxDiscount5 | Sconti massimi | dec |  |
| MaxDiscount6 | Sconti massimi | dec |  |
| MaxDiscount7 | Sconti massimi | dec |  |
| MessageVerbosityLevel | Livello di verbosità dei messaggi per le validazioni fallite | enum |  |
| [MultipleQuantity](salescontrolline.md#multiplequantity) | Quantità multipla | dec |  |
| PromotionId | Id della promozione | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| SalesControlId | Id del controllo commerciale | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| SeverityLevel | Livello di serietà | enum |  |
| StartAmountRange | Inizio Scaglione importo | dec |  |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| TrademarkId | Id del trademark | text | 50 |
| UomId | Id dell'unità di misura \(di vendita o di imballo\) | text | 20 |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup
* 2: CustomerPriceGroup
* 3: CustomerGroup
* 6: StatisticClass
* 7: ShipmentSiteCountry

## ItemEncodingType

* 0: Item
* 1: ItemDiscountGroup
* 2: ItemSeries

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...
