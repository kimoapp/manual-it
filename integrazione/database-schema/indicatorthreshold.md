---
description: Soglie degli indicatori
---

# IndicatorThreshold

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Code |  | text | 50 |
| [EncodingKey](indicatorthreshold.md#encodingkey) | Chiave | text | 50 |
| [EncodingType](indicatorthreshold.md#encodingtype) | Prefisso | enum |  |
| EndRange | Fine quantità | dec |  |
| Icon |  | text | 100 |
| Id | Id | text | 50 |
| StartRange | Inizio quantità | dec |  |
| Style |  | text | text |
| [Type](indicatorthreshold.md#type) |  | enum |  |

## EncodingKey

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata l'indicatore

## EncodingType

I campi EncodingType ed EncodingKey permettono di definire quali sono le entità a cui va applicata l'indicatore.
* 0: Undefined
* 1: Document

## Type

* 0: MarkupPercentage
* 1: MarkupAmount
* 2: SaleMarginPercentage
* 3: SaleMarginAmount
