# Promozioni

https://app.gitbook.com/o/-Kv3UZ4g8dSfYFvyl9tO/s/-LPpk5IsUPUlxEIxH-lc/funzionalita/promozioniIn Kimo è possibile configurare 3 tipi di promozioni:

* **Classic**: Permette di definire una condizione di vendita che modifica prezzo e/o sconti di uno o più articoli
* **Kit**: Permette di definire una confezione di articoli vendibili in quantità prestabilite a livello di promozione, la quantità di vendita è il risultato della moltiplicazione tra i campi SuggestedQty e NumberOfKits
* **N+M**: Permette di definire una quantità omaggio rapportata alla quantità di vendita (Es: Ogni 5 articoli venduti se ne riceve uno in omaggio, vendendo 10 articoli se ne ricevono 2 in omaggio)

### Filtro attivazione promozioni

L'accesso alle promozioni viene regolato dalla tabella PromotionFilter.\
In questa tabella valorizzando i campi EncodingType ed EncodingKey si può specificare la 'categoria' a cui fa riferimento la promozione.\
La categoria specificata viene abilitata o meno in base al valore assunto dal campo Included.\
I tipi di Encoding disponibili sono:

* 00: Generica
* 01: Gruppo clienti
* 02: Metodo di pagamento
* 03: Classe statistica
* 04: Cliente
* 05: Agente incluso senza necessità di specificare ulteriori filtri
* 05-Exclusive: Esclude gli altri agenti dalla promozione
* DocType: Esclude gli altri tipi di documento
* Channel-Exclusive: Esclude gli altri canali

In aggiunta ai campi EncodingType ed EncodingKey è possibile filtrare per 10 magazzini differenti; i magazzini sono rappresentati da 10 differenti campi della tabella col nome WarehouseId(X).\
Il campo WarehousesIncluded indica se devono essere inclusi o esclusi quelli specificati.\
Se si vogliono abilitare tutti i magazzini gestiti è sufficiente inserire 0 nel flag WarehousesIncluded  e lasciare null i campi WarehouseId(X).

### Promotion

I principali campi che permettono di alterare il calcolo del prezzo di un articolo a livello di testata promozione sono:

* **CustomerDiscountRule** -> Regola che indica come gestire/ricavare gli sconti all'interno della promozione:
  * 0: default o quelli associati al gruppo cliente per clienti Michelangelo
  * 1: Include quelli associati al cliente
  * 2: Associati al costo dell'articolo (ItemCost)
  * 3: Mantiene gli sconti definiti nel prezzo unitario
  * 4: Prende il prezzo unitario lordo
  * 5: Prende il prezzo unitario netto
  * 6: Prende il prezzo standard
* **PricePrintingRule** -> Indica se mostrare il prezzo in promozione o meno:
  * 0: Viene mostrato
  * 1: Non viene mostrato
* **MinItems** -> Numero minimo di articoli per poter attivare la promozione
* **MinQty** -> Quantità di vendita minima per poter attivare la promozione
* **MinAmount** -> Amount minimo per poter attivare la promozione

### PromotionLine

Gli articoli inclusi nella promozione possono essere indicati a livello di PromotionLine inserendo nel campo EncodingType:

* AR: Articolo specifico
* TT: Produttore
* FN: Gruppo merceologico (Specifica per clienti Michelangelo)
* SN: Serie articoli
* FF: Ignore
* CV: Categoria sconti vendita
* ItemCollection: Collezione articolo
* ItemLine: Famiglia statistica fornitore
* MAGO\_IG: Gruppo merceologico con livello specifico (Specifica per clienti MAGO)

In base al tipo di Encoding inserito, andrà specificato nell'EncodingKey il codice a cui applicare la promozione (Es: Nel caso di EncodingType = AR il campo EncodingKey va valorizzato col codice di un articolo). \
Anche in questo caso i due campi sono regolati dal flag 'Included' che indica se la categoria indicata deve avere una funzione inclusiva o esclusiva.

Principali campi che permettono di alterare il funzionamento della riga in promozione:

* **MaxDiscount** -> Definisce lo sconto massimo per la riga della promozione
* **GiftPaidQty** -> Nelle promozioni N+M indica la quantità N
* **GiftFreeQty** ->  Nelle promozioni N+M indica la quantità M
* **GiftQtyMode** -> Indica se la quantità in omaggio è inclusa nel valore GiftPaidQty ( Es: Promo 2+1 -> Se 0 GiftPaidQty  è 3, se 1 GiftPaidQty è 2)
* **GiftItemId** -> Codice dell'articolo in omaggio: in promozioni N + M in cui l'articolo in omaggio è diverso da quello venduto
* **QuantityRangeN\_Quantity** -> Quantità di inizio
* **QuantityRangeN\_Discounts** -> Sconti personalizzati per la quantità indicata
* **QuantityRangeN\_ImposedUnitPrice** -> Prezzo unitario personalizzato per la quantità specificata

### Utilizzo promozioni Kimo SFA

L'attivazione di una promozione può essere eseguita nei seguenti modi:

* Accedendo all'editor delle promozioni:
  *   È possibile accedere all'editor delle promozioni tramite l'apposita funzionalità presente nel menù,&#x20;

      si verrà reindirizzati all'elenco delle promozioni; una volta scelta la promozione verrà visualizzato l'elenco degli articoli presenti al suo interno.

![](<../.gitbook/assets/Simulator Screen Shot - iPad Pro (9.7-inch) - 2019-10-14 at 15.48.28\_framed.png>)

* Tappando la stellina: Per gli articoli in cui è presente almeno una promozione c'è la possibilità di configurare il layout facendo si che venga visualizzata la stellina delle promozioni <img src="../.gitbook/assets/Screenshot 2019-10-14 at 14.28.04.png" alt="" data-size="original"> . Tappando su questa stellina si potrà accedere direttamente all'interno dell'editor della riga promozione.\

* Cambiando condizione di vendita nell'editor della riga documento:
  *   Per poter eseguire questa operazione deve essere stato appositamente

      configurato il layout [DocumentLineEditor](../interfaccia-utente/sfa/layout/list/documentlineeditorcontext.md).\
      N.B. Non tutte le promozione possono essere attivate con questo metodo, le promozioni complesse devono necessariamente essere attivate dall'editor

![](<../.gitbook/assets/Simulator Screen Shot - iPad Pro (9.7-inch) - 2019-10-14 at 15.56.53\_framed.png>)

* Attivazione automatica:
  * Nella tabella delle promozioni è presente un campo, ActivationMode, che definisce la modalità di attivazione della promozione, utilizzando la modalità automatica (1) l'articolo, già all'interno del catalogo, mostrerà ed utilizzerà il prezzo calcolato con la condizione di vendita definita nella promozione
