# PriceCalculation

| Valore | Descrizione |
| :--- | :--- |
| [**Algorithm**](pricecalculation.md#algorithm) | Algoritmo per il calcolo dei prezzi |
| [**MinimumNumberOfQuantityRangesToActivateNotification**](pricecalculation.md#minimumnumberofquantityrangestoactivatenotification) | Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni \(e non considerarli semplicemente come articoli di cui è richiesta una quantità minima\) |
| [**PricePerQtyMultiplierMode**](pricecalculation.md#priceperqtymultipliermode) | Modalità di applicazione del moltiplicatore prezzi |
| [**PromotionDiscountsPositionMode**](pricecalculation.md#promotiondiscountspositionmode) | Posizione degli sconti provenienti dalle promozioni \(testata o righe\) |
| [**RetailPriceDecimalDigitsRounding**](pricecalculation.md#retailpricedecimaldigitsrounding) | Numero di cifre decimali nei prezzi retail |
| [**RetailPricesIncludeVat**](pricecalculation.md#retailpricesincludevat) | I prezzi retail includono l'IVA |
| [**ShouldShowAllPricesFromPriceCalculator**](pricecalculation.md#shouldshowallpricesfrompricecalculator) | Nella lista di tutte le condizioni di vendita mostra tutti i prezzi ottenibile dall'algoritmo di calcolo prezzi |
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

## PromotionDiscountsPositionMode

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Accoda gli sconti a quelli già presenti nella riga documento, ignorando gli sconti a zero \(es. lo sconto '0 + 0 + 5' nella riga della riga promozione viene salvato nella riga del documento come '5'.
* 1 =&gt; Accoda gli sconti a quelli già presenti nella riga documento, preservando gli zero \(es. lo sconto '0 + 0 + 5' nella riga della riga promozione viene salvato nella riga del documento come '0 + 0 + 5'.

## RetailPriceDecimalDigitsRounding

**Tipo:** Int32

## RetailPricesIncludeVat

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; No
* 1 =&gt; Yes

## ShouldShowAllPricesFromPriceCalculator

**Tipo:** Boolean

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

