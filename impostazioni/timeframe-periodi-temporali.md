# Timeframe \(periodi temporali\)

## Tipi di timeframe:

* [Per anno](timeframe-periodi-temporali.md#per-anno)
* [Per mese](timeframe-periodi-temporali.md#per-mese)
* [Per settimana](timeframe-periodi-temporali.md#per-settimana)
* [Per giorno](timeframe-periodi-temporali.md#per-giorno)
* [Year To Date](timeframe-periodi-temporali.md#year-to-date)

## Descrizione

In alcuni contesti possono essere configurati degli intervalli di tempo predefiniti \(timeframe\) per i quali eseguire le ricerche delle informazioni: ad esempio, per filtare i documenti storici \(Documenti da Erp\) per uno specifico intervallo temporale, o per filtrare le informazioni nella smart BI.

Queste configurazioni sono definite attraverso delle business rule, come "ErpDocument\Timeframes" \(vedi la sezione relativa alle business rules per l'elenco completo\).

La business rule potrà essere definita con un valore tipo:

LastDayFromToday30\|CurrentWeek\|LastCalendarWeek\|CurrentMonth\|LastCalendarMonth\|YearToToday\|LastMonthFromToday12

dove ogni elemento indica il tipo di timeframe.

Per molti timeframe può essere indicato un valore numerico, che assume di default valore 1 se non specificato. Ad esempio:

* LastMonthFromYesterday: indica l'ultimo mese, fino a ieri
* LastMonthFromYesterday6: indica gli ultimi 6 mesi, fino a ieri.

Di seguito è riportato l'elenco delle chiavi utilizzabili per definire i timeframe nelle impostazioni.

## Per Anno

#### N = 1, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastYearFromYesterday | 2019-06-15 | 2020-06-15 | Ultimo anno fino a ieri |
| LastYearFromToday | 2019-06-16 | 2020-06-16 | Ultimo anno fino ad oggi |
| LastCalendarYear | 2019-01-01 | 2019-12-31 | 2019 |
| CurrentYear | 2020-01-01 | 2020-12-31 | 2020 |

#### **N = 3**, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastYearFromYesterday3 | 2017-06-15 | 2020-06-15 | Ultimi 3 anni fino a ieri |
| LastYearFromToday3 | 2017-06-16 | 2020-06-16 | Ultimi 3 anni fino ad oggi |
| LastCalendarYear3 | 2017-01-01 | 2019-12-31 | 2017 - 2019 |
| CurrentYear3 | 2018-01-01 | 2020-01-01 | 2018 - 2020 |

## Per mese

#### N = 1, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastMonthFromYesterday | 2020-05-15 | 2020-06-15 | Ultimo mese fino a ieri |
| LastMonthFromToday | 2020-05-16 | 2020-06-16 | Ultimo mese fino ad oggi |
| LastCalendarMonth | 2020-05-01 | 2020-05-31 | Ultimo mese \(Maggio 2020\) |
| CurrentMonth | 2020-06-01 | 2020-06-30 | Mese corrente \(Giugno 2020\) |

#### N = 3, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastMonthFromYesterday3 | 2020-03-15 | 2020-06-15 | Ultimi 3 mesi fino a ieri |
| LastMonthFromToday3 | 2020-03-16 | 2020-06-16 | Ultimi 3 mesi fino ad oggi |
| LastCalendarMonth3 | 2020-03-01 | 2020-05-31 | Ultimi 3 mesi \(Marzo 2020 - Maggio 2020\) |
| CurrentMonth3 | 2020-04-01 | 2020-06-30 | Aprile 2020 - Giugno 2020 |

## Per settimana

#### N = 1, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastWeekFromYesterday | 2020-06-09 | 2020-06-15 | Ultima settimana fino a ieri |
| LastWeekFromToday | 2020-06-10 | 2020-06-16 | Ultima settimana fino ad oggi |
| LastCalendarWeek | 2020-06-08 | 2020-06-14 | Ultima settimana |
| CurrentWeek | 2020-06-15 | 2020-06-21 | Settimana corrente |

#### N = 3, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastWeekFromYesterday3 | 2020-05-26 | 2020-06-15 | Ultime 3 settimane fino a ieri |
| LastWeekFromToday3 | 2020-05-27 | 2020-06-16 | Ultime 3 settimane fino ad oggi |
| LastCalendarWeek3 | 2020-05-25 | 2020-06-14 | Ultime 3 settimane |
| CurrentWeek3 | 2020-06-01 | 2020-06-21 | Ultime 3 settimane compresa quella corrente |

## Per giorno

#### N = 1, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastDayFromYesterday | 2020-06-15 | 2020-06-15 | Ieri |
| LastDayFromToday | 2020-06-16 | 2020-06-16 | Oggi |
| CurrentDay | 2020-06-16 | 2020-06-16 | Oggi |

#### N = 3, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| LastDayFromYesterday3 | 2020-06-13 | 2020-06-15 | Ultimi 3 giorni fino a ieri |
| LastDayFromToday3 | 2020-06-14 | 2020-06-16 | Ultimi 3 giorni fino ad oggi |
| CurrentDay3 | 2020-06-14 | 2020-06-16 | Ultimi 3 giorni fino ad oggi |

## Year To Date

#### N = 1, Data di Riferimento = 2020-06-16

| Chiave | Da | A | Descrizione |
| :--- | :--- | :--- | :--- |
| YearToYesterday | 2020-01-01 | 2020-06-15 | YTD - dal 1° gennaio a ieri |
| YearToToday | 2020-01-01 | 2020-06-16 | YTD - dal 1° gennaio ad oggi |
| YearToEndOfCurrentMonth | 2020-01-01 | 2020-06-16 | Dal 1° gennaio a fine mese corrente |
| YearToEndOfLastMonth | 2020-01-01 | 2020-05-31 | Dal 1° gennaio a fine mese scorso |

