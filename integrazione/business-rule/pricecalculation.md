# PriceCalculation
Algorithm 
----
**Descrizione:** Algoritmo per il calcolo dei prezzi <br> 
**Tipo:** String <br> 

MinimumNumberOfQuantityRangesToActivateNotification 
----
**Descrizione:** Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni (e non considerarli semplicemente come articoli di cui è richiesta una quantità minima) <br> 
**Tipo:** Int32 <br> 

PricePerQtyMultiplierMode 
----
**Descrizione:** Modalità di applicazione del moltiplicatore prezzi <br> 
**Tipo:** Enum <br> 
**Valore di default:** 0 <br> 
**Valori:**
* 0 => Applicato sul totale del documento
* 1 => Applicato sul prezzo unitario

RetailPricesIncludeVat 
----
**Descrizione:** I prezzi retail includono l'IVA <br> 
**Tipo:** Enum <br> 
**Valore di default:** 0 <br> 
**Valori:**
* 0 => No
* 1 => Yes

TotalAmountDecimalDigitsRounding 
----
**Descrizione:** Numero di cifre decimali negli importi totali <br> 
**Tipo:** Int32 <br> 
**Valore di default:** 2 <br> 

UnitPriceDecimalDigitsRounding 
----
**Descrizione:** Numero di cifre decimali nei prezzi unitari <br> 
**Tipo:** Int32 <br> 
**Valore di default:** 5 <br> 

UnitPriceRoundingMode 
----
**Descrizione:** Modalità di arrotondamento per i prezzi unitaru <br> 
**Tipo:** Enum <br> 
**Valore di default:** 0 <br> 
**Valori:**
* 0 => Mathematical
* 1 => RoundUp
* 2 => RoundDown

