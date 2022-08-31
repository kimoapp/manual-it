# Funzioni di trasformazione "speciali"

In alcune situazioni è necessario fare delle particolari trasformazioni nei dati importati o esportati da Kimo. Ad esempio, può essere utile impostare un valore fisso su un certo campo esportato all'ERP.

Kimo permette di definire queste trasformazioni attraverso i campi "ImportTransformations" e "ExportTransformations" della tabella IntegratorMapping, indicando la funzione da applicare attraverso il suo nome.

Alcune funzioni prevedono dei parametri, in tal caso andranno specificati usando il carattere ':'. Ad esempio, per indicare di impostare il valore 'KIMO' attraverso la funzione "FixedValueAsString", si definità come impostazione "FixedValueAsString:KIMO" nel campo "ExportTransformations".

### Import

| Funzione     | Descrizione                                                                                                                                                | Parametri/esempi di utilizzo                                                                                                                                                                                                                                                                                                                       |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| QueryAsLong  | <p>Permette di inserire all'interno di una query un valore come intero, anche se in Kimo quel campo è definito come stringa.<br>Non prevede parametri.</p> | Utile nelle situazioni in cui vanno letti direttamente i dati dall'ERP, es. i Documenti da Erp "online", ed il campo Id nell'Erp è di tipo intero, mentre in Kimo è di tipo stringa. Se si facesse la query come stringa, si potrebbe ottenere un errore: grazie a questa trasformazione, la query viene fatta considerando il campo come intero.  |
| StringToHash | <p>Converte una stringa in un hash. <br>Non prevede parametri.</p>                                                                                         | Può essere utile per "accorciare" un campo "ID" che sarebbe più lungo dei 50 caratteri previsti come lunghezza massima da Kimo (es. un campo composto concatenando più campi, la cui lunghezza totale supera appunto tale limite).                                                                                                                 |



### Export

| Funzione           | Descrizione                                                                                                            | Parametri/esempi di utilizzo                                                                                           |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| FixedValueAsString | Esporta sul campo in cui è usata questa trasformazione un valore fisso, indicato come parametro.                       | <p>Es. FixedValueAsString:KIMO<br>Esporta sempre il valore 'KIMO' su quel campo.</p>                                   |
| RemovePrefix       | Rimuove un eventuale prefisso indicato come parametro, se presente all'inizio del valore esportato.                    | <p>Es. <br>RemovePrefix:Account_<br><em></em>Se il valore da esportare è 'Account_123', verrà esportato come '123'</p> |
| StringToInteger    | Esporta all'ERP un campo che in Kimo è definito di tipo stringa come intero, per evitare errori nelle query di INSERT. |                                                                                                                        |

