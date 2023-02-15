# ItemAvailability

| Valore | Descrizione |
| :--- | :--- |
| [**FilterMode**](itemavailability.md#filtermode) | Modalità di filtro delle disponibilità durante la preparazione dati per gli agenti |
| [**GlobalAvailabilityCompanyLeadTime**](itemavailability.md#globalavailabilitycompanyleadtime) | Tempo di consegna globale |
| [**GlobalAvailabilityMode**](itemavailability.md#globalavailabilitymode) | Modalità di calcolo della disponibilità globale |
| [**LogisticCenterAvailabilityCompanyLeadTime**](itemavailability.md#logisticcenteravailabilitycompanyleadtime) | Tempo di consegna dal centro logistico |
| [**QtyField**](itemavailability.md#qtyfield) | Campo da considerare per verificare la quantità disponibile |
| [**WarehouseAvailabilityCompanyLeadTime**](itemavailability.md#warehouseavailabilitycompanyleadtime) | Tempo di consegna dal magazzino corrente |

## FilterMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Per magazzino dell'utente/agente
* 1 =&gt; Nessun filtro

## GlobalAvailabilityCompanyLeadTime

**Tipo:** Int32  
**Valore di default:** 2

## GlobalAvailabilityMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Indicata direttamente nel campo 'GlobalAvailability' di 'ItemOfflineAvailability'
* 1 =&gt; Calcolata dalle disponibilità nei magazzini

## LogisticCenterAvailabilityCompanyLeadTime

**Tipo:** Int32  
**Valore di default:** 2

## QtyField

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; SalesQty
* 1 =&gt; NumberOfPacks

## WarehouseAvailabilityCompanyLeadTime

**Tipo:** Int32  
**Valore di default:** 1
.