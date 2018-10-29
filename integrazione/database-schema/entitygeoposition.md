# EntityGeoposition

  
 **Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione | Note |
| :--- | :--- | :--- | :--- | :--- |
| AddressCity | Città | text | 40 |  |
| AddressCountry | Paese | text | 20 |  |
| AddressCountrySubdivision | Provincia | text | 20 |  |
| AddressLine | Indirizzo | text | 80 |  |
| AddressPostCode | CAP | text | 20 |  |
| CreationDate | Data di creazione | dt |  |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |  |
| EntityId | Id sull'ERP dell'entità gestita da Kimo | text | 50 |  |
| EntityStatus | Campo che definisce lo stato del record | enum |  | 0: ImportedFromErp, 1: ExportedToErp, 2: ImportedByErp, 3: ExportingToErp, 4: Deleted, 5: CommittingExportToErp, 6: ToExportToErp, 7: Editing, 8: UploadedToServer |
| EntityTypeId | Tipo di entità | text | 50 |  |
| Id | Id | text | 50 |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |  |
| Latitude | Latitudine | dec |  |  |
| Longitude | Longitude | dec |  |  |
| SyncReference | Riferimento | text | 50 |  |
| UploadToServerTimeStamp |  | dt |  |  |

