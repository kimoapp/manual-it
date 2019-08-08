# Documenti di vendita

I documenti di vendita generabili in Kimo partono da due famiglie base:

* Preventivi
* Ordini

La differenza fondamentale in Kimo è che i Documenti appartenenti alla famiglia dei Preventivi, a differenza degli Ordini, possono essere inviati all'Erp.

A partire da un Preventivo è comunque possibile effettuare una trasformazione in Ordine.

Le 2 entità principali a cui fanno riferimento i Documenti sono:

* [Document](../../integrazione/database-schema/document.md)
* [DocumentLine](../../integrazione/database-schema/documentline.md)

La fase di inserimento Documento deve necessariamente partire da un Account oppure un Budget.  
In base a regole e configurazioni definite, tentando di creare un documento, verranno proposti i tipi di documento disponibili.

### 

