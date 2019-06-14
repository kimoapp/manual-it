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
0: NullableText&ltbr&gt;2: NullableInteger&ltbr&gt;3: NullableDate&ltbr&gt;5: SingleSelectionList&ltbr&gt;6: NullableUnsignedDecimal&ltbr&gt;7: NullableDecimal&ltbr&gt;9: MultiSelectionList&ltbr&gt;25: NullableBoolean&ltbr&gt;100: Label


