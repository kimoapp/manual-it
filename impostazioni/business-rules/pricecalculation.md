# PriceCalculation

| Valore| Descrizione |
| :--- | :--- |
| [**Algorithm**](#algorithm)** | Algoritmo per il calcolo dei prezzi |
| [**MinimumNumberOfQuantityRangesToActivateNotification**](#minimumnumberofquantityrangestoactivatenotification)** | Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni (e non considerarli semplicemente come articoli di cui è richiesta una quantità minima) |
| [**PricePerQtyMultiplierMode**](#priceperqtymultipliermode)** | Modalità di applicazione del moltiplicatore prezzi |
| [**RetailPricesIncludeVat**](#retailpricesincludevat)** | I prezzi retail includono l'IVA |
| [**TotalAmountDecimalDigitsRounding**](#totalamountdecimaldigitsrounding)** | Numero di cifre decimali negli importi totali |
| [**UnitPriceDecimalDigitsRounding**](#unitpricedecimaldigitsrounding)** | Numero di cifre decimali nei prezzi unitari |
| [**UnitPriceRoundingMode**](#unitpriceroundingmode)** | Modalità di arrotondamento per i prezzi unitaru |

$h2 Algorithm 
-----
**Tipo:** String	 

$h2 MinimumNumberOfQuantityRangesToActivateNotification 
-----
**Tipo:** Int32	 

$h2 PricePerQtyMultiplierMode 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Applicato sul totale del documento
* 1 => Applicato sul prezzo unitario

$h2 RetailPricesIncludeVat 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => No
* 1 => Yes

$h2 TotalAmountDecimalDigitsRounding 
-----
**Tipo:** Int32	 
**Valore di default:** 2	 

$h2 UnitPriceDecimalDigitsRounding 
-----
**Tipo:** Int32	 
**Valore di default:** 5	 

$h2 UnitPriceRoundingMode 
-----
**Tipo:** Enum	 
**Valore di default:** 0	 
**Valori:**
* 0 => Mathematical
* 1 => RoundUp
* 2 => RoundDown

