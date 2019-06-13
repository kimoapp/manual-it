---
description: Campi delle schede marketing
---
# MarketingFormField

<br>
**Chiavi**
- *Id*
- FormTypeId, FieldId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| :--- | :--- | :--- | :--- | :--- |
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
0: NullableText<br&gt;2: NullableInteger<br&gt;3: NullableDate<br&gt;5: SingleSelectionList<br&gt;6: NullableUnsignedDecimal<br&gt;7: NullableDecimal<br&gt;9: MultiSelectionList<br&gt;25: NullableBoolean<br&gt;100: Label


