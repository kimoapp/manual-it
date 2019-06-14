---
description: Controlli commerciali sulle righe dei documenti di vendita
---
# SalesControlDocumentLine

**Chiavi**

- *Id*
- SalesControlType, ChannelsEnabled, ItemId, VariableItemId, SalesUomId, AccountId, SalesAgentId, DocumentTypeId, CurrencyId, SeasonId, TrademarkId, StartDate, EndDate

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| MaxDiscount1 | Sconti massimi | dec |  |
| MaxDiscount2 | Sconti massimi | dec |  |
| MaxDiscount3 | Sconti massimi | dec |  |
| MaxDiscount4 | Sconti massimi | dec |  |
| MaxDiscount5 | Sconti massimi | dec |  |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](salescontroldocumentline.md#salescontroltype) | Tipo di controllo | enum |  |
| SalesUomId | Id dell'unità di misura di vendita | text | 20 |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](salescontroldocumentline.md#severitylevel) | Livello di serietà | enum |  |
| StartDate | Data inizio validità | date |  |
| TrademarkId | Id del trademark | text | 50 |
| Value | Valore \(vedi documentazione dei Controlli Commerciali\) | dec |  |
| VariableItemId | Id dell'articolo variante | text | 50 |
## SalesControlType

0: None&lt;br&gt;1: Sconto massimo&lt;br&gt;2: Quantità minima&lt;br&gt;3: Prezzo minimo&lt;br&gt;4: Vendita per quantità disponibile&lt;br&gt;5: Ripristino condizioni di vendita per quantità non conforme al confezionamento&lt;br&gt;6: Prezzo Unitario non a zero
## SeverityLevel

0: Error&lt;br&gt;1: Warning


