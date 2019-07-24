# Tipo Report

Un Tipo Report è un modello di Report.  
Ciascun Tipo Report è relativo ad un contesto.  
Il contesto in questo caso definisce il modello dati \(data context\) a cui il report fà riferimento.  
Ciascun tipo report referenzia un modello realizzato con tecnologia Active Report e costituito da un file con estensione RPX.  
Questa funzionalità consente di definire report personalizzati che estendono quelli già presenti in Kimo.

I contesti supportati sono i seguenti:

## Document

| Attributo | Tipo | Descrizione |
| :--- | :--- | :--- |
| Document.DocumentFamilyId | DocumentFamilyId | Id della famiglia documento |
| Document.DocumentTypeId | string | Id del tipo documento |
| Document.NumbersRegistryId | string | Id del numero registrazione |
| Document.Number | string | Numero documento |
| Document.DocumentDate | date | Data documento |
| Document.PricesReferenceDate | date | Data di riferimento per i prezzi |

TODO Informazioni parziali estratte dalla classe: Document.Data.cs. Essendo presenti delle annotazione le informazioni potrebbero essere estratte in automatico. Capire se spostare nella documentazione interna.

