# B2b\Cart

| Valore| Descrizione |
| :--- | :--- |
| [**CartFromReassortmentNameTemplate**](b2bcart.md#cartfromreassortmentnametemplate) | Template per il nome del carrello creato dal riassortimento |
| [**CreditLimitCheck**](b2bcart.md#creditlimitcheck) | Tipo di controllo sul fido al checkout |
| [**MaxQtyValidationType**](b2bcart.md#maxqtyvalidationtype) | Tipo di validazione della quantità |
| [**ReassortmentTypeAsConstraintIsMandatory**](b2bcart.md#reassortmenttypeasconstraintismandatory) | Tipo Riassortimento come vincolo obbligatorio |
| [**ShipmentSiteIsMandatory**](b2bcart.md#shipmentsiteismandatory) | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](b2bcart.md#validatepricesobsolescence) | Abilita la validazione dei prezzi al checkout |

-----
**Tipo:** Template	 
**Valori:**

* CreationDate
* ReassortmentType.Description

-----
**Tipo:** Enum	 
**Valori:**

* 0 => Nessun controllo
* 1 => Importo totale (con IVA e spese accessorie incluse)
* 2 => Totale merce (IVA esclusa)

-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**

* 0 => Nessun controllo
* 1 => In confronto alla disponibilità

-----
**Tipo:** Boolean	 

-----
**Tipo:** Boolean	 

-----
**Tipo:** Boolean	 
**Valore di default:** True

