---
description: Campi delle schede marketing
---

# MarketingFormField

  
 **Chiavi**

* _Id_
* FormTypeId, FieldId

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Column | Colonna | int |  |
| DefaultValue | Valore di default | text | text |
| Description | Descrizione | text | 255 |
| FieldId | Id del campo | text | 50 |
| [FieldType](marketingformfield.md#fieldtype) | Tipo del campo | enum |  |
| FormTypeId | Id del tipo di scheda | text | 50 |
| Id | Id | text | 50 |
| Row | Riga | int |  |

## FieldType

0: NullableText&lt;br&gt;2: NullableInteger&lt;br&gt;3: NullableDate&lt;br&gt;5: SingleSelectionList&lt;br&gt;6: NullableUnsignedDecimal&lt;br&gt;7: NullableDecimal&lt;br&gt;9: MultiSelectionList&lt;br&gt;25: NullableBoolean&lt;br&gt;100: Label

