# B2b\Cart

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| CartFromReassortmentNameTemplate | Template per il nome del carrello creato dal riassortimento | Template | <ul>  <li>CreationDate</li> <li>ReassortmentType.Description</li></ul>|  |
| CreditLimitCheck | Tipo di controllo sul fido al checkout | Enum | <ul>  <li>0 => Nessun controllo</li> <li>1 => Importo totale (con IVA e spese accessorie incluse)</li> <li>2 => Totale merce (IVA esclusa)</li></ul>|  |
| MaxQtyValidationType | Tipo di validazione della quantità | Enum | <ul>  <li>0 => Nessun controllo</li> <li>1 => In confronto alla disponibilità</li></ul>| 0 |
| ReassortmentTypeAsConstraintIsMandatory | Tipo Riassortimento come vincolo obbligatorio | Boolean | <ul> </ul>|  |
| ShipmentSiteIsMandatory | Destinazione merci obbligatoria | Boolean | <ul> </ul>|  |
| ValidatePricesObsolescence | Abilita la validazione dei prezzi al checkout | Boolean | <ul> </ul>| True |

