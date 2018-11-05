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
| [FieldType](#fieldtype) | Tipo del campo | enum |  |
| FormTypeId | Id del tipo di scheda | text | 50 |
| Id | Id | text | 50 |
| Row | Riga | int |  |

FieldType
---
0: NullableText<br>2: NullableInteger<br>3: NullableDate<br>5: SingleSelectionList<br>6: NullableUnsignedDecimal<br>7: NullableDecimal<br>9: MultiSelectionList<br>25: NullableBoolean<br>100: Label

