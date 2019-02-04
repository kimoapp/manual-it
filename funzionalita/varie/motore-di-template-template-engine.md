# Motore di template \(Template Engine\)

Kimo utilizza un motore di template \(Template Engine\) per comporre alcune stringhe personalizzabili. Ad esempio, tale motore viene utilizzato per renderizzare i layout basati sull'HTML \(come quelli per la scheda cliente e scheda articolo\) o alcune Regole di Business, come  "Document\QuantitiesSummaryTemplate".

## Sintassi

## Funzioni per la formattazione

| Funzione | Parametri | Scopo |
| :--- | :--- | :--- |
| formatter.ToQuantity | decimal value | Formattazione come quantità \(fino a 5 decimali\) |
| formatter.ToUnitPrice | decimal value | Formattazione come prezzo unitario \(es. con 2 zeri dopo la virgola e fino a 5 decimali\) |
| formatter.ToTotalPrice | decimal value | Formattazione come importo totale \(es. con 2 zeri dopo la virgola e fino a 2 decimali\) |
| formatter.NumberToInvariantString | decimal value | Converte un numero in una stringa nel formato "invariant" \(usando il '.' per i decimali a prescindere dalla lingua e senza alcun separatore per le migliaia\) |
| formatter.ToMonthName | int month | Dato il numero di un mese, ne restituisce il nome |

## Funzioni di utilità

| Funzione | Parametri | Scopo |
| :--- | :--- | :--- |
| utils.Take | object lista, int count | Data una lista di valori, prende i primi n espressi dal parametro "count" |
|  |  |  |

