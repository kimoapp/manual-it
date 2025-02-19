---
description: Return Merchandise Authorization (Rma)
---

# Rma

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| Amount | Importo | dec |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| [EntityStatus](rma.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ErpDocumentId | Id del documento da erp di riferimento | text | 50 |
| ErpDocumentLineId | Id riga del Documento da erp | text | 50 |
| ErpDocumentLineReference | Riga del Documento da erp di riferimento | text | 50 |
| ErpDocumentReference | Documento da erp di riferimento | text | 50 |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeDecimal4 | Campo decimale libero | dec |  |
| FreeDecimal5 | Campo decimale libero | dec |  |
| FreeLookup1 | Campo per dati tabellati | text | 50 |
| FreeLookup2 | Campo per dati tabellati | text | 50 |
| FreeLookup3 | Campo per dati tabellati | text | 50 |
| FreeLookup4 | Campo per dati tabellati | text | 50 |
| FreeLookup5 | Campo per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | 50 |
| FreeText2 | Campo testo libero | text | 50 |
| FreeText3 | Campo testo libero | text | 50 |
| FreeText4 | Campo testo libero | text | 50 |
| FreeText5 | Campo testo libero | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| ItemDescription | Descrizione articolo | text | 130 |
| ItemId | Id dell'articolo | text | 50 |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| Notes | Note | text | text |
| RmaDate | Data dell'Rma | date |  |
| SalesQty | Quantità di vendita | dec |  |
| SalesUomId | Unità di misura di vendita | text | 50 |
| [Status](rma.md#status) | Stato del rma | enum |  |
| SyncReference | Riferimento | text | 50 |
| UnitsPerPack | Unità per confezione | dec |  |
| UploadToServerTimeStamp |  | dt |  |

## EntityStatus

* 0: ImportedFromErp
* 1: ExportedToErp
* 2: ImportedByErp
* 3: ExportingToErp
* 4: Deleted
* 5: CommittingExportToErp
* 6: ToExportToErp
* 7: Editing
* 8: UploadedToServer
* 9: StartedUploadToServer
* 10: EditingPending
* -1: Undefined

## Status

* 0: Open
* 1: Confirmed
* -1: Undefined
