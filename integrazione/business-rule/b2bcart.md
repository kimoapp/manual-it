# B2b\Cart
CartFromReassortmentNameTemplate 
----
 **Descrizione:** Template per il nome del carrello creato dal riassortimento <br>
**Tipo:** Template <br>
* CreationDate
* ReassortmentType.Description

CreditLimitCheck 
----
 **Descrizione:** Tipo di controllo sul fido al checkout <br>
**Tipo:** Enum <br>
* 0 => Nessun controllo
* 1 => Importo totale (con IVA e spese accessorie incluse)
* 2 => Totale merce (IVA esclusa)

MaxQtyValidationType 
----
 **Descrizione:** Tipo di validazione della quantità <br>
**Tipo:** Enum <br>
**Valore di default:** 0 <br>
**Valori:**
* 0 => Nessun controllo
* 1 => In confronto alla disponibilità

ReassortmentTypeAsConstraintIsMandatory 
----
 **Descrizione:** Tipo Riassortimento come vincolo obbligatorio <br>
**Tipo:** Boolean <br>

ShipmentSiteIsMandatory 
----
 **Descrizione:** Destinazione merci obbligatoria <br>
**Tipo:** Boolean <br>

ValidatePricesObsolescence 
----
 **Descrizione:** Abilita la validazione dei prezzi al checkout <br>
**Tipo:** Boolean <br>
**Valore di default:** True <br>
**Valori:**

