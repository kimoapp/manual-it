# B2b\Cart

| Valore | Descrizione |
| :--- | :--- |
| [**CartFromReassortmentNameTemplate**](b2bcart.md#cartfromreassortmentnametemplate)\*\* | Template per il nome del carrello creato dal riassortimento |
| [**CreditLimitCheck**](b2bcart.md#creditlimitcheck)\*\* | Tipo di controllo sul fido al checkout |
| [**MaxQtyValidationType**](b2bcart.md#maxqtyvalidationtype)\*\* | Tipo di validazione della quantità |
| [**ReassortmentTypeAsConstraintIsMandatory**](b2bcart.md#reassortmenttypeasconstraintismandatory)\*\* | Tipo Riassortimento come vincolo obbligatorio |
| [**ShipmentSiteIsMandatory**](b2bcart.md#shipmentsiteismandatory)\*\* | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](b2bcart.md#validatepricesobsolescence)\*\* | Abilita la validazione dei prezzi al checkout |

## $h2 CartFromReassortmentNameTemplate

**Tipo:** Template  
**Valori:**

* CreationDate
* ReassortmentType.Description

## $h2 CreditLimitCheck

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Nessun controllo
* 1 =&gt; Importo totale \(con IVA e spese accessorie incluse\)
* 2 =&gt; Totale merce \(IVA esclusa\)

## $h2 MaxQtyValidationType

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Nessun controllo
* 1 =&gt; In confronto alla disponibilità

## $h2 ReassortmentTypeAsConstraintIsMandatory

**Tipo:** Boolean

## $h2 ShipmentSiteIsMandatory

**Tipo:** Boolean

## $h2 ValidatePricesObsolescence

**Tipo:** Boolean  
**Valore di default:** True

