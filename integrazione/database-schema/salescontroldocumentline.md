---
description: Controlli commerciali sulle righe dei documenti di vendita
---

# SalesControlDocumentLine

**Chiavi**

* _Id_
* SalesControlType, ChannelsEnabled, ItemEncodingType, ItemEncodingKey, VariableItemId, VariableId1, VariableValueId1, VariableId2, VariableValueId2, UomType, UomId, AccountEncodingType, AccountEncodingKey, SalesAgentId, DocumentTypeId, CurrencyId, PromotionId, SeasonId, TrademarkId, StartDate, EndDate, StartQuantityRange, EndQuantityRange

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountEncodingKey | Chiave identificativa per i clienti \(codice, gruppo, ...\) | text | 50 |
| [AccountEncodingType](salescontroldocumentline.md#accountencodingtype) | Tipo della chiave identificativa per i clienti | enum |  |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndDate | Data fine validità | date |  |
| EndQuantityRange | Fine Scaglione quantità | dec |  |
| Id | Id | text | 50 |
| ItemEncodingKey | Chiave identificativa per gli articoli \(codice, gruppo, ...\) | text | 50 |
| [ItemEncodingType](salescontroldocumentline.md#itemencodingtype) | Tipo della chiave identificativa per gli articoli | enum |  |
| MaxDiscount1 | Sconti massimi | dec |  |
| MaxDiscount2 | Sconti massimi | dec |  |
| MaxDiscount3 | Sconti massimi | dec |  |
| MaxDiscount4 | Sconti massimi | dec |  |
| MaxDiscount5 | Sconti massimi | dec |  |
| [MessageVerbosityLevel](salescontroldocumentline.md#messageverbositylevel) | Livello di verbosità dei messaggi per le validazioni fallite | enum |  |
| [MultipleQuantity](salescontroldocumentline.md#multiplequantity) | Quantità multipla | dec |  |
| PromotionId | Id della promozione | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](salescontroldocumentline.md#salescontroltype) | Tipo di controllo | enum |  |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](salescontroldocumentline.md#severitylevel) | Livello di serietà | enum |  |
| StartDate | Data inizio validità | date |  |
| StartQuantityRange | Inizio Scaglione quantità | dec |  |
| TrademarkId | Id del trademark | text | 50 |
| UomId | Id dell'unità di misura \(di vendita o di imballo\) | text | 20 |
| [UomType](salescontroldocumentline.md#uomtype) | Tipo dell'unità di misura \(di vendita o di imballo\) | enum |  |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |
| VariableId1 | Id variante | text | 50 |
| VariableId2 | Id variante | text | 50 |
| VariableItemId | Id dell'articolo variante | text | 50 |
| VariableValueId1 | Valore variante | text | 50 |
| VariableValueId2 | Valore variante | text | 50 |

## AccountEncodingType

* 0: Account
* 1: CustomerDiscountGroup

## ItemEncodingType

* 0: Item
* 1: ItemDiscountGroup

## MessageVerbosityLevel

* 0: Default
* 1: DoNotShowValue

## MultipleQuantity

Se la quantità è 50 e la quantità multipla è 10, lo scaglione può essere applicato solo a quantità come 50, 60, 70, ... e non a quantità come 51, 52, ...

## SalesControlType

* 0: None
* 1: Sconto massimo
* 2: Quantità minima
* 3: Prezzo minimo
* 4: Vendita per quantità disponibile
* 5: Ripristino condizioni di vendita per quantità non conforme al confezionamento
* 6: Prezzo Unitario non a zero

## SeverityLevel

* 0: Error
* 1: Warning

## UomType

* 0: SalesUom
* 1: PackUom
