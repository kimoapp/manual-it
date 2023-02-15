# B2b\Cart

| Valore | Descrizione |
| :--- | :--- |
| [**CartNameTemplate**](b2bcart.md#cartnametemplate) | Template per il nome del carrello |
| [**CheckoutActionPriority**](b2bcart.md#checkoutactionpriority) | Ordine azioni di checkout |
| [**ConstraintFields**](b2bcart.md#constraintfields) | Campi che costituiscono un vincolo obbligatorio |
| [**CreditLimitCheck**](b2bcart.md#creditlimitcheck) | Tipo di controllo sul fido al checkout |
| [**MenuItems**](b2bcart.md#menuitems) | Elementi del menu |
| [**ShipmentSiteIsMandatory**](b2bcart.md#shipmentsiteismandatory) | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](b2bcart.md#validatepricesobsolescence) | Abilita la validazione dei prezzi al checkout |
| [**WarehousesForCollectOnSite**](b2bcart.md#warehousesforcollectonsite) | Magazzini per il ritiro al banco |

## CartNameTemplate

**Tipo:** Template  
**Valore di default:** ${CreationDate}  
**Valori:**

* CreationDate
* ItemCollection.Description
* ItemCollection.Id
* ReassortmentType.Description
* Season.Description
* Season.Id
* Trademark.Description
* Trademark.Id

## CheckoutActionPriority

**Tipo:** Valori separati da pipe  
**Valori:**

* 0 =&gt; Conferma carrello
* 1 =&gt; Invia carrello all'agente

## ConstraintFields

**Tipo:** Valori separati da pipe  
**Valori:**

* ItemCollection
* ReassortmentType
* Season
* Trademark

## CreditLimitCheck

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Nessun controllo
* 1 =&gt; Importo totale \(con IVA e spese accessorie incluse\)
* 2 =&gt; Totale merce \(IVA esclusa\)

## MenuItems

**Tipo:** Valori separati da pipe  
**Valori:**

* 1 =&gt; Dettagli carrello
* 2 =&gt; Nuovo carrello
* 3 =&gt; Elimina carrello
* 4 =&gt; Stampa carrello
* 5 =&gt; Duplica carrello
* 6 =&gt; Carica da Excel
* 7 =&gt; Carrelli in gestione
* 8 =&gt; Storico carrelli

## ShipmentSiteIsMandatory

**Tipo:** Boolean

## ValidatePricesObsolescence

**Tipo:** Boolean  
**Valore di default:** True

## WarehousesForCollectOnSite

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Solo con disponibilità
* 1 =&gt; Tutti
.