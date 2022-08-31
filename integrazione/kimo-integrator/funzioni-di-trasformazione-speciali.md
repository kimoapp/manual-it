# Funzioni di trasformazione "speciali"



Import

| Funzione     | Descrizione                                                                                                               | Parametri/esempi di utilizzo                                                                                                                                                                                                                                                                                                                       |
| ------------ | ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| QueryAsLong  | Permette di inserire all'interno di una query un valore come intero, anche se in Kimo quel campo è definito come stringa. | Utile nelle situazioni in cui vanno letti direttamente i dati dall'ERP, es. i Documenti da Erp "online", ed il campo Id nell'Erp è di tipo intero, mentre in Kimo è di tipo stringa. Se si facesse la query come stringa, si potrebbe ottenere un errore: grazie a questa trasformazione, la query viene fatta considerando il campo come intero.  |
| StringToHash | Converte una stringa in un hash.                                                                                          | Può essere utile per "accorciare" un campo "ID" che sarebbe più lungo dei 50 caratteri previsti come lunghezza massima da Kimo (es. un campo composto concatenando più campi, la cui lunghezza totale supera appunto tale limite).                                                                                                                 |
