# PriceCalculation
Algorithm 
----
**Descrizione:** Algoritmo per il calcolo dei prezzi
**Tipo:** String
**Valore di default:** 
**Valori:**

MinimumNumberOfQuantityRangesToActivateNotification 
----
**Descrizione:** Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni (e non considerarli semplicemente come articoli di cui è richiesta una quantità minima)
**Tipo:** Int32
**Valore di default:** 
**Valori:**

PricePerQtyMultiplierMode 
----
**Descrizione:** Modalità di applicazione del moltiplicatore prezzi
**Tipo:** Enum
**Valore di default:** 0
**Valori:**
* 0 => Applicato sul totale del documento
* 1 => Applicato sul prezzo unitario

RetailPricesIncludeVat 
----
**Descrizione:** I prezzi retail includono l'IVA
**Tipo:** Enum
**Valore di default:** 0
**Valori:**
* 0 => No
* 1 => Yes

TotalAmountDecimalDigitsRounding 
----
**Descrizione:** Numero di cifre decimali negli importi totali
**Tipo:** Int32
**Valore di default:** 2
**Valori:**

UnitPriceDecimalDigitsRounding 
----
**Descrizione:** Numero di cifre decimali nei prezzi unitari
**Tipo:** Int32
**Valore di default:** 5
**Valori:**

UnitPriceRoundingMode 
----
**Descrizione:** Modalità di arrotondamento per i prezzi unitaru
**Tipo:** Enum
**Valore di default:** 0
**Valori:**
* 0 => Mathematical
* 1 => RoundUp
* 2 => RoundDown

