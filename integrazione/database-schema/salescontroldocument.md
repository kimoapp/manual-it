---
description: Controlli commerciali sui documenti di vendita
---
# SalesControlDocument

<br>
**Chiavi**
- *Id*
- SalesControlType, ChannelsEnabled, AccountId, SalesAgentId, DocumentTypeId, CurrencyId, SeasonId, TrademarkId, StartDate, EndDate, StartAmountRange, EndAmountRange
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| ChannelsEnabled | Indica per quali canali è abilitato (se non specificato vale per tutti i canali) | enum |  |
| CurrencyId | Id della valuta | text | 50 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndAmountRange | Fine Scaglione importo | dec |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| [SalesControlType](#salescontroltype) | Tipo di controllo | enum |  |
| SeasonId | Id della stagione | text | 50 |
| [SeverityLevel](#severitylevel) | Livello di serietà | enum |  |
| StartAmountRange | Inizio Scaglione importo | dec |  |
| StartDate | Data inizio validità | date |  |
| TrademarkId | Id del trademark | text | 50 |
| Value | Valore (vedi documentazione dei Controlli Commerciali) | dec |  |

SalesControlType
---
0: None<br>1: Importo minimo<br>2: Sconto medio totale massimo
SeverityLevel
---
0: Error<br>1: Warning


