# MarketingFormField

<br>
**Chiavi**
- *Id*
- FormTypeId, FieldId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| Column | Colonna | int |  |
| DefaultValue | Valore di default | text | text |
| Description | Descrizione | text | 255 |
| FieldId | Id del campo | text | 50 |
| [FieldType](#FieldType) | Tipo del campo | enum |  |
| FormTypeId | Id del tipo di scheda | text | 50 |
| Id | Id | text | 50 |
| Row | Riga | int |  |

A FieldType
---
0: NullableText
2: NullableInteger
3: NullableDate
5: SingleSelectionList
6: NullableUnsignedDecimal
7: NullableDecimal
9: MultiSelectionList
25: NullableBoolean
100: Label

