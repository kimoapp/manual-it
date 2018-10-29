# SalesControlDocumentLine

<br>
**Chiavi**
- *Id*
- SalesControlType, ChannelsEnabled, ItemId, SalesUomId, AccountId, SalesAgentId, DocumentTypeId, CurrencyId, SeasonId, TrademarkId, StartDate, EndDate
<br><br>

| Campo | Descrizione | Tipo | Dimensione | Note |
| --- | --- | --- | --- | --- |
| AccountId | Id del cliente | text | 50 |  |
| ChannelsEnabled | Indica per quali canali è abilitato (se non specificato vale per tutti i canali) | enum |  |  |
| CurrencyId | Id della valuta | text | 50 |  |
| DocumentTypeId | Id del tipo documento | text | 50 |  |
| EndDate | Data fine validità | date |  |  |
| Id | Id | text | 50 |  |
| ItemId | Id dell'articolo | text | 50 |  |
| MaxDiscount1 | Sconti massimi | dec |  |  |
| MaxDiscount2 | Sconti massimi | dec |  |  |
| MaxDiscount3 | Sconti massimi | dec |  |  |
| MaxDiscount4 | Sconti massimi | dec |  |  |
| MaxDiscount5 | Sconti massimi | dec |  |  |
| SalesAgentId | Id dell'agente | text | 50 |  |
| SalesControlType | Tipo di controllo | enum |  | 0: None, 1: Sconto massimo, 2: Quantità minima, 3: Prezzo minimo |
| SalesUomId | Id dell'unità di misura di vendita | text | 20 |  |
| SeasonId | Id della stagione | text | 50 |  |
| StartDate | Data inizio validità | date |  |  |
| TrademarkId | Id del trademark | text | 50 |  |
| Value | Valore (vedi documentazione dei Controlli Commerciali) | dec |  |  |

