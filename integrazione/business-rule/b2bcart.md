# B2b\Cart
[CartFromReassortmentNameTemplate](#cartfromreassortmentnametemplate)	 
**Descrizione:** Template per il nome del carrello creato dal riassortimento	 
**Tipo:** Template	 
[CreditLimitCheck](#creditlimitcheck)	 
**Descrizione:** Tipo di controllo sul fido al checkout	 
**Tipo:** Enum	 
[MaxQtyValidationType](#maxqtyvalidationtype)	 
**Descrizione:** Tipo di validazione della quantità	 
**Tipo:** Enum	 
**Valore di default:** 0	 
[ReassortmentTypeAsConstraintIsMandatory](#reassortmenttypeasconstraintismandatory)	 
**Descrizione:** Tipo Riassortimento come vincolo obbligatorio	 
**Tipo:** Boolean	 
[ShipmentSiteIsMandatory](#shipmentsiteismandatory)	 
**Descrizione:** Destinazione merci obbligatoria	 
**Tipo:** Boolean	 
[ValidatePricesObsolescence](#validatepricesobsolescence)	 
**Descrizione:** Abilita la validazione dei prezzi al checkout	 
**Tipo:** Boolean	 
**Valore di default:** True	 
CartFromReassortmentNameTemplate 
-----

**Valori:**
* CreationDate
* ReassortmentType.Description

CreditLimitCheck 
-----

**Valori:**
* 0 => Nessun controllo
* 1 => Importo totale (con IVA e spese accessorie incluse)
* 2 => Totale merce (IVA esclusa)

MaxQtyValidationType 
-----

**Valori:**
* 0 => Nessun controllo
* 1 => In confronto alla disponibilità

