# B2b\Cart
CartFromReassortmentNameTemplate 
----
**Descrizione:** Template per il nome del carrello creato dal riassortimento
**Tipo:** Template
**Valore di default:** 
**Valori:**
* CreationDate
* ReassortmentType.Description

CreditLimitCheck 
----
**Descrizione:** Tipo di controllo sul fido al checkout
**Tipo:** Enum
**Valore di default:** 
**Valori:**
* 0 => Nessun controllo
* 1 => Importo totale (con IVA e spese accessorie incluse)
* 2 => Totale merce (IVA esclusa)

MaxQtyValidationType 
----
**Descrizione:** Tipo di validazione della quantità
**Tipo:** Enum
**Valore di default:** 0
**Valori:**
* 0 => Nessun controllo
* 1 => In confronto alla disponibilità

ReassortmentTypeAsConstraintIsMandatory 
----
**Descrizione:** Tipo Riassortimento come vincolo obbligatorio
**Tipo:** Boolean
**Valore di default:** 
**Valori:**

ShipmentSiteIsMandatory 
----
**Descrizione:** Destinazione merci obbligatoria
**Tipo:** Boolean
**Valore di default:** 
**Valori:**

ValidatePricesObsolescence 
----
**Descrizione:** Abilita la validazione dei prezzi al checkout
**Tipo:** Boolean
**Valore di default:** True
**Valori:**

