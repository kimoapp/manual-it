# PriceCalculation

| Valore | Descrizione |
| :--- | :--- |
| [**Algorithm**](pricecalculation.md#algorithm) | Algoritmo per il calcolo dei prezzi |
| [**MinimumNumberOfQuantityRangesToActivateNotification**](pricecalculation.md#minimumnumberofquantityrangestoactivatenotification) | Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni \(e non considerarli semplicemente come articoli di cui è richiesta una quantità minima\) |
| [**PricePerQtyMultiplierMode**](pricecalculation.md#priceperqtymultipliermode) | Modalità di applicazione del moltiplicatore prezzi |
| [**RetailPricesIncludeVat**](pricecalculation.md#retailpricesincludevat) | I prezzi retail includono l'IVA |
| [**TotalAmountDecimalDigitsRounding**](pricecalculation.md#totalamountdecimaldigitsrounding) | Numero di cifre decimali negli importi totali |
| [**UnitPriceDecimalDigitsRounding**](pricecalculation.md#unitpricedecimaldigitsrounding) | Numero di cifre decimali nei prezzi unitari |
| [**UnitPriceRoundingMode**](pricecalculation.md#unitpriceroundingmode) | Modalità di arrotondamento per i prezzi unitaru |

## Algorithm

**Tipo:** String

## MinimumNumberOfQuantityRangesToActivateNotification

**Tipo:** Int32

## PricePerQtyMultiplierMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Applicato sul totale del documento
* 1 =&gt; Applicato sul prezzo unitario

## RetailPricesIncludeVat

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; No
* 1 =&gt; Yes

## TotalAmountDecimalDigitsRounding

**Tipo:** Int32  
**Valore di default:** 2

## UnitPriceDecimalDigitsRounding

**Tipo:** Int32  
**Valore di default:** 5

## UnitPriceRoundingMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Mathematical
* 1 =&gt; RoundUp
* 2 =&gt; RoundDown


