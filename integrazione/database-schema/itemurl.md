---
description: Risorse 'online' degli articoli (schede tecniche online, immagini, ...)
---

# ItemUrl

**Chiavi**

* _Id_
* ItemId, VariableId1, VariableValueId1, UrlTypeId, Url

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Caption | Titolo immagine | text | text |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| Priority |  | int |  |
| Url | Url collegato all'articolo | text | 500 |
| [UrlTypeId](itemurl.md#urltypeid) |  | enum |  |
| VariableId1 | Id Variante 1 | text | 50 |
| VariableValueId1 | Valore Variante 1 | text | 50 |

## UrlTypeId

* 0: Undefined
* 1: Image
* 2: OnlineForm
* 3: Video
* 4: Document
* 5: Other
.