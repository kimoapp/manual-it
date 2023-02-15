# DocumentSearch

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](documentsearch.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**DocumentTypeTemplate**](documentsearch.md#documenttypetemplate) | Template con cui formattare la descrizione del Tipo Documento |
| [**FooterTemplate**](documentsearch.md#footertemplate) | TTemplate per il footer della ricerca documenti \(es. per visualizzare dei totali\) |
| [**KeywordSearchFields**](documentsearch.md#keywordsearchfields) | Campi per la ricerca testuale |
| [**Timeframes**](documentsearch.md#timeframes) | Periodi |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** SearchType\|DocumentType\|Timeframe

## DocumentTypeTemplate

**Tipo:** String  
**Valore di default:** ${DocumentTypeDescription}

## FooterTemplate

**Tipo:** String  
**Valore di default:** ${AmountLabel}  ${Amount}

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Number\|AccountName\|AccountName2

## Timeframes

**Tipo:** Valori separati da pipe  
**Valore di default:** LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12
.