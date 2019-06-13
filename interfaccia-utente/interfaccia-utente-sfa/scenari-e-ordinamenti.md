# Scenari e ordinamenti

Uno Scenario permette di definire un insieme di regole \(filtri ed ordinamenti\) da applicare ai dati di un Contesto visualizzati secondo uno specifico Layout. 

![](../../.gitbook/assets/image%20%2834%29.png)

![](../../.gitbook/assets/image%20%2820%29.png)

**Nota bene:**

Context Id: i contesti che possono essere utilizzati sono i seguenti:

* AccountsSearchContext
* ContactsSearchContext
* ItemsSearchContext
* DocumentsSearchContext
* ErpDocumentsSearchContext
* FilesSearchContext
* ReassortmentContext
* ActivitiesSearchContext
* RecurrentAcivitiesSearchContext
* ReceivableBookTableRowContext
* BudgetDrillDownTableRowContext
* BudgetLineTableRowContext
* CartsSearchContext

Tipo ricerca: i tipi di ricerca che possono essere utilizzati sono i seguenti:

* Account
  * AllCustomers 
  * AllCustomersAndShipmentSites 
  * Locked 
  * HasOpenInstallments 
  * HasUnpaidInstallments 
  * HasExpiredInstallments
  * ShipmentSitesByHeadOffice 
  * Prospects
  *  HasOpenCarts
* Contact
  * AllContacts 
* Items
  * AllItems
  * AvailableItems
  * IdrolabOnline
  * Idrolab 
* Document
  * AllDocuments
  * ActiveDocuments
  * ExpiredDocuments
  * CompletedDocuments
  * ArchivedDocuments
* ErpDocument
  * AllDocuments 
* Files: AllFiles
* Reassortment
  * AllReassortmentItems 
* Activities
  * AllActivities
  * ToPlan 
* RecurrentAcivities
  * AllRecurrences 
* ReceivableInstallment
  * AllInstallments 
* Budget
  * AllBudgets 
* BudgetLines
  * AllBudgetLines 
* Carts
  * OpenCarts

Layout Id: i layout che possono essere utilizzati sono i seguenti:

* AccountsSearchLayout 
* ContactsSearchLayout 
* ItemsSearchLayout
*  DocumentsSearchLayout
* ErpDocumentsSearchLayout 
* FilesSearchLayout 
* ReassortmentLayout 
* ActivitiesSearchLayout 
* RecurrentAcivitiesSearchLayout 
* ReceivableBookTableRowLayout
* BudgetDrillDownTableRowLayout
* BudgetLineTableRowContext
* CartsSearchLayout

Campi ordinamento: può essere specificato un elenco di campi da usare separati da virgola. Ciascun campo deve essere un attributo del contesto specificato. 

Priorità ordinamento: è un numero da 0 a N che rappresenta l'ordine di apparizione dello scenario rispetto agli altri. Lo scenario con la priorità 0 è il primo da sinistra.

