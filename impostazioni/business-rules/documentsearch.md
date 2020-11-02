# DocumentSearch

| Valore | Descrizione |
| :--- | :--- |
| [**AdvancedSearchFields**](documentsearch.md#advancedsearchfields) | Campi per la ricerca avanzata |
| [**DocumentTypeTemplate**](documentsearch.md#documenttypetemplate) | Template con cui formattare la descrizione del Tipo Documento |
| [**FooterTemplate**](documentsearch.md#footertemplate) | TTemplate per il footer della ricerca documenti \(es. per visualizzare dei totali\) |
| [**KeywordSearchFields**](documentsearch.md#keywordsearchfields) | Campi per la ricerca testuale |

## AdvancedSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** SearchType\|DocumentType

## DocumentTypeTemplate

**Tipo:** String  
**Valore di default:** ${DocumentTypeDescription}

## FooterTemplate

**Tipo:** String  
**Valore di default:** ${NumberLabel}: ${Number} - ${AmountLabel}: ${Amount}

## KeywordSearchFields

**Tipo:** Valori separati da pipe  
**Valore di default:** Number\|AccountName\|AccountName2
