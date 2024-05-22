---
description: Articoli non a stock
---

# NonStockItem

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| BaseSalesUomId | Id dell'unità di misura di vendita base | text | 10 |
| BitwiseValues | Gestione dei Bitwise | text | n.d. |
| ChannelsEnabled | Indica per quali canali è abilitato l'articolo \(se non specificato vale per tutti i canali\) | enum |  |
| CollectionId | Id della collezione | text | 50 |
| CreationDate | Data di creazione | dt |  |
| Description | Descrizione breve dell'articolo | text | 130 |
| DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| EndCustomerPrice | Prezzo articolo al cliente finale | dec |  |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | n.d. |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeDateTime1 | Campo data libero | dt |  |
| FreeDateTime2 | Campo data libero | dt |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeLookup1 | Campo per dati tabellati | text | 50 |
| FreeLookup2 | Campo per dati tabellati | text | 50 |
| FreeLookup3 | Campo per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FreeText4 | Campo testo libero | text | text |
| FreeText5 | Campo testo libero | text | text |
| GenderId | Id genere | text | 50 |
| Id | Id | text | 50 |
| IsVisibleOnItemsSearch | Indica se l'articolo debba essere nascosto in fase di ricerca | bool |  |
| ItemDiscountGroupId | Id del gruppo sconti articolo | text | 50 |
| ItemGroupLevel1Id | Id gruppo articoli livello 1 | text | 50 |
| ItemGroupLevel2Id | Id gruppo articoli livello 2 | text | 50 |
| ItemGroupLevel3Id | Id gruppo articoli livello 3 | text | 50 |
| ItemGroupLevel4Id | Id gruppo articoli livello 4 | text | 50 |
| ItemSeriesId | Id serie articolo | text | 50 |
| [ItemType](nonstockitem.md#itemtype) | Tipo articolo | enum |  |
| LeadTime | Tempo di approvvigionamento | int |  |
| LineId | Id della linea | text | 50 |
| LongDescription | Descrizione lunga dell'articolo | text | text |
| [LotManagementType](nonstockitem.md#lotmanagementtype) | Tipo di gestione dei lotti | enum |  |
| ManufacturerId | Id del produttore | text | 50 |
| ManufacturerItemId | Id dell'articolo produttore | text | 50 |
| Notes | Note | text | text |
| Prebuy | Gestione 'prebuy' | bool |  |
| SeasonId | Id della stagione | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| VatRateId | Id dell'aliquota IVA | text | 50 |

## ItemType

* 0: Normal
* 1: Manual
* 2: Note
* 3: ModelItem
* 4: VariableItem
* 5: Idrolab
* 6: Jolly
* 7: NonStockItem
* 8: IlDataPool

## LotManagementType

* 0: No
* 1: Mandatory
* 2: Optional
