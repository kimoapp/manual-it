# Articolo a variante

La gestione degli articoli a variante prevede la presenza di un solo record nella tabella Item che rappresenta l'articolo modello, contraddistinto dal campo Item.ItemType con valore 3.  
Le varianti dell'articolo sono gestite nell'entità ItemVariable.  
In questa entità vengono riportate per ogni articolo tutte le combinazioni di varianti.  
Kimo può gestire fino a due tipi di varianti, i tipi e i valori assunti per ogni tipo di variante devono necessariamente essere presenti nelle apposite anagrafiche.  
Per ciascun articolo modello è possibile gestire varianti di tipo diverso.  
  
**Esempio di due articoli gestiti con varianti di diverso tipo:**

### Item \(Modello articolo\)

| ItemId | ItemDescription | ItemType |
| :--- | :--- | :--- |
| scp01 | Scarpa | 3 |
| csc01 | Casco | 3 |

### ItemVariable \(Articolo con varianti\)

| ModelItemId | VariableItemId | VariableId1 | VariableId2 | VariableValueId1 | VariableValueId2 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| scp01 | scp01\_rossa\_35 | COLORE | TAGLIA | rossa | 35 |
| scp01 | scp01\_rossa\_36 | COLORE | TAGLIA | rossa | 36 |
| scp01 | scp01\_blu\_35 | COLORE | TAGLIA | blu | 35 |
| scp01 | scp01\_blu\_36 | COLORE | TAGLIA | blu | 36 |
| csc01 | csc01\_ABS\_M | MATERIALE | SIZE | ABS | M |
| csc01 | csc01\_ABS\_L | MATERIALE | SIZE | ABS | L |
| csc01 | csc01\_KEVLAR\_M | MATERIALE | SIZE | KEVLAR | M |
| csc01 | csc01\_KEVLAR\_L | MATERIALE | SIZE | KEVLAR | L |

### Variable \(Tipi di varianti\)

| Id | TypeId | Description |
| :--- | :--- | :--- |
| COLORE | COLORI | Colore dell'articolo |
| TAGLIA | TAGLIE | Taglia dell'articolo |
| SIZE | SIZE | Size dell'articolo |
| MATERIALE | MATERIALI | Materiale dell'articolo |

### VariableValue \(Valori gestiti per ogni tipo di variante\)

| VariableId | Description | SortPriority | ValueId |
| :--- | :--- | :--- | :--- |
| COLORE | Rosso | 1 | rosso |
| COLORE | Blu | 2 | blu |
| TAGLIA | 35 | 1 | 35 |
| TAGLIA | 36 | 2 | 36 |
| SIZE | M | 1 | M |
| SIZE | L | 2 | L |
| MATERIALE | ABS | 1 | ABS |
| MATERIALE | KEVLAR | 2 | KEVLAR |

In fase di inserimento ordine, per gli articoli a variante, viene proposto un editor della riga che facilita la selezione delle varianti e l'inserimento delle quantità di vendita: [Editor riga](../documenti-di-vendita/inserimento-riga.md#editor-riga-articoli-a-variante)

