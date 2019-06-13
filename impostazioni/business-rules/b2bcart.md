# B2b\Cart

| Valore| Descrizione |
| :--- | :--- |
| [**CartFromReassortmentNameTemplate**](#cartfromreassortmentnametemplate)** | Template per il nome del carrello creato dal riassortimento |
| [**CreditLimitCheck**](#creditlimitcheck)** | Tipo di controllo sul fido al checkout |
| [**MaxQtyValidationType**](#maxqtyvalidationtype)** | Tipo di validazione della quantità |
| [**ReassortmentTypeAsConstraintIsMandatory**](#reassortmenttypeasconstraintismandatory)** | Tipo Riassortimento come vincolo obbligatorio |
| [**ShipmentSiteIsMandatory**](#shipmentsiteismandatory)** | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](#validatepricesobsolescence)** | Abilita la validazione dei prezzi al checkout |

$h2 CartFromReassortmentNameTemplate 
-----
**Tipo:** Template	 
**Valori:**
* CreationDate
* ReassortmentType.Description

$h2 CreditLimitCheck 
-----
**Tipo:** Enum	 
**Valori:**
* 0 => Nessun controllo
* 1 => Importo totale (con IVA e spese accessorie incluse)
* 2 => Totale merce (IVA esclusa)

$h2 MaxQtyValidationType 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Nessun controllo
* 1 => In confronto alla disponibilità

$h2 ReassortmentTypeAsConstraintIsMandatory 
-----
**Tipo:** Boolean	 

$h2 ShipmentSiteIsMandatory 
-----
**Tipo:** Boolean	 

$h2 ValidatePricesObsolescence 
-----
**Tipo:** Boolean	 
**Valore di default:** True

