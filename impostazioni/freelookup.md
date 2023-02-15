# FreeLookup

Una FreeLookup è una lista di coppie di valori: codice, descrizione.  
Tipicamente una Freelookup svolge la funzione di tabella di decodifica valori.  
Ciascuna FreeLookup è associata ad un campo di tipo freelookup di una Entity, di cui è specificato l'indice 

Es. 

| Entity | Index | Campo referenziato |
| :--- | :--- | :--- |
| Account | 1 | Account.Freelookup1 |

I valori di ciascuna FreeLookup possono essere importati dall'Erp o inseriti direttamente da Console di Amministrazione di Kimo.  
Una FreeLookup importata dall'Erp è readonly per Kimo.

Es.

| Entity | Index | Codice | Descrizione |
| :--- | :--- | :--- | :--- |
| Account | 1 | 10 | Mario Rossi |
| Account | 1 | 20 | Luigi Bianchi |

.