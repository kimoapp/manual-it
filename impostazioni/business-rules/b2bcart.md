# B2b\Cart

| Valore | Descrizione |
| :--- | :--- |
| [**CartFromReassortmentNameTemplate**](b2bcart.md#cartfromreassortmentnametemplate) | Template per il nome del carrello creato dal riassortimento |
| [**CreditLimitCheck**](b2bcart.md#creditlimitcheck) | Tipo di controllo sul fido al checkout |
| [**ReassortmentTypeAsConstraintIsMandatory**](b2bcart.md#reassortmenttypeasconstraintismandatory) | Tipo Riassortimento come vincolo obbligatorio |
| [**ShipmentSiteIsMandatory**](b2bcart.md#shipmentsiteismandatory) | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](b2bcart.md#validatepricesobsolescence) | Abilita la validazione dei prezzi al checkout |

## CartFromReassortmentNameTemplate

**Tipo:** Template  
**Valori:**

* CreationDate
* ReassortmentType.Description

## CreditLimitCheck

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Nessun controllo
* 1 =&gt; Importo totale \(con IVA e spese accessorie incluse\)
* 2 =&gt; Totale merce \(IVA esclusa\)

## ReassortmentTypeAsConstraintIsMandatory

**Tipo:** Boolean

## ShipmentSiteIsMandatory

**Tipo:** Boolean

## ValidatePricesObsolescence

**Tipo:** Boolean  
**Valore di default:** True

