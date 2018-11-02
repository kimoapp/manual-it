# PriceCalculation

<br><br>

| Valore | Descrizione | Tipo | Valori | Valore di default |
| --- | --- | --- | --- | --- |
| Algorithm | Algoritmo per il calcolo dei prezzi | String | <ul> </ul>|  |
| MinimumNumberOfQuantityRangesToActivateNotification | Numero minimo di scaglioni quantità necessari per attivare la gestione degli scaglioni (e non considerarli semplicemente come articoli di cui è richiesta una quantità minima) | Int32 | <ul> </ul>|  |
| PricePerQtyMultiplierMode | Modalità di applicazione del moltiplicatore prezzi | Enum | <ul>  <li>0 => Applicato sul totale del documento</li> <li>1 => Applicato sul prezzo unitario</li></ul>| 0 |
| RetailPricesIncludeVat | I prezzi retail includono l'IVA | Enum | <ul>  <li>0 => No</li> <li>1 => Yes</li></ul>| 0 |
| TotalAmountDecimalDigitsRounding | Numero di cifre decimali negli importi totali | Int32 | <ul> </ul>| 2 |
| UnitPriceDecimalDigitsRounding | Numero di cifre decimali nei prezzi unitari | Int32 | <ul> </ul>| 5 |
| UnitPriceRoundingMode | Modalità di arrotondamento per i prezzi unitaru | Enum | <ul>  <li>0 => Mathematical</li> <li>1 => RoundUp</li> <li>2 => RoundDown</li></ul>| 0 |

