# Tipo Report

Un Tipo Report è un modello di Report.  
Ciascun Tipo Report è relativo ad un contesto.  
Il contesto in questo caso definisce il modello dati \(data context\) a cui il report fà riferimento.  
Ciascun tipo report referenzia un modello realizzato con tecnologia Active Report e costituito da un file con estensione RPX.  
Questa funzionalità consente di definire report personalizzati che estendono quelli già presenti in Kimo.

Un Tipo Report dispone dei seguenti attributi:

* Codice: identificativo univoco del Tipo Report
* Descrizione
* File Template: nome del file con estensione RPX
* Contesto: il contesto definisce il modello dati a cui il report fa riferimento. Attualmente l'unico disponibile è "[Document](document-data-model.md)".
* Priorità:  indica il l'ordine in cui compare il Tipo Report nella lista dei Tipi Report 
* Modalità di stampa: 
  * NULL: dati non raggruppati
  * VariableItems: dati raggruppati in base al ItemVariableId
  * GroupedByManufacturer: dati raggruppati in base al ManufacturerId



