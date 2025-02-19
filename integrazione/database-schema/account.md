---
description: Account (clienti, prospect, destinazioni merci)
---

# Account

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| [AccountFilterId](account.md#accountfilterid) | Id del filtro clienti | text | 50 |
| [AccountTypeId](account.md#accounttypeid) | Tipo di account \(cliente, prospect, destinazione merci, ... | enum |  |
| AddressCity | Città | text | 40 |
| AddressCountry | Paese | text | 20 |
| AddressCountrySubdivision | Provincia | text | 20 |
| AddressLine | Indirizzo | text | 200 |
| AddressPostCode | CAP | text | 20 |
| BankAbi | Codice ABI | text | 5 |
| BankCab | Codice CAB | text | 5 |
| BankCc | Codice CC | text | 20 |
| BankCin | Codice CIN | text | 1 |
| BankCountryCode | Codice del paese | text | 5 |
| BankIban | Codice IBAN | text | 50 |
| BankIbanCheckDigits | Check digits dell'IBAN | text | 5 |
| CarrierId | Id del vettore | text | 50 |
| CertifiedMail | Mail certificata \(PEC - Posta Elettronica Certificata | text | 100 |
| [ChargeForUnpackaged](account.md#chargeforunpackaged) | Addebita fuori confezione \(sfusi\) | enum |  |
| CigCode | Codice CIG | text | 50 |
| ContactInfo | Info di contatto del cliente | text | text |
| CreationDate | Data di creazione | dt |  |
| [CreationReason](account.md#creationreason) | Indica se è un nuovo cliente, se è un cliente modificato o se è stato creato un cliente a partire da un prospect | enum |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| CupCode | Codice Cup | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerDiscountGroupId | Id del gruppo sconti cliente | text | 50 |
| CustomerGroupId | Id del gruppo cliente | text | 50 |
| CustomerPriceGroupId | Id del gruppo prezzi cliente | text | 50 |
| [CustomerTypeId](account.md#customertypeid) | Indica se il cliente è una persona fisica o un'organizzazione | enum |  |
| DeliveryDateTypeId | Id del tipo di data consegna | text | 50 |
| DeliveryRouteId | Id del giro di consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| DiscountType | Logica da applicare con gli sconti durante il calcolo dei prezzi | text | 50 |
| EditMode | Edit Mode | text | 50 |
| [EntityStatus](account.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| ExceptionsPriceListId | Id del listino eccezioni associato al cliente | text | 50 |
| Fax | Fax | text | 50 |
| FiscalCode | Codice fiscale | text | 30 |
| FixedDiscount | Sconto importo | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeBoolean6 | Campo booleano libero | bool |  |
| FreeBoolean7 | Campo booleano libero | bool |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeLookup1 | Campo per dati tabellati | text | 50 |
| FreeLookup2 | Campo per dati tabellati | text | 50 |
| FreeLookup3 | Campo per dati tabellati | text | 50 |
| FreeLookup4 | Campo per dati tabellati | text | 50 |
| FreeLookup5 | Campo per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FreeText4 | Campo testo libero | text | text |
| FreeText5 | Campo testo libero | text | text |
| GoodsAspectId | Id dell'aspetto beni | text | 50 |
| HeadOfficeId | Id della sede legale in caso si tratti di un record per identificare una destinazione merce | text | 50 |
| Id | Id | text | 50 |
| InstallmentsCurrencyId | Id della valuta delle partite aperte | text | 50 |
| InvoiceDiscountId | Id dello sconto fattura | text | 50 |
| IpaCode | Codice IPA | text | 20 |
| IsDefaultShipmentSite | Indica se l'indirizzo del cliente è quello di default per la consegna | bool |  |
| IsDefaultShipmentSite2 | Indica se l'indirizzo del cliente è quello di default per la consegna \(2\) | bool |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LanguageId | Id della lingua | text | 50 |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| [Level](account.md#level) | Indica il 'livello di qualità' del cliente | enum |  |
| Locked | Indica se il cliente è bloccato | bool |  |
| LogisticCallRequest |  | bool |  |
| LogisticDeliveryToFloor |  | bool |  |
| LogisticLimitedTrafficZone |  | bool |  |
| LogisticNotes |  | text | text |
| LogisticOpeningDays |  | text | 30 |
| LogisticOpeningTimes |  | text | 50 |
| LogisticPhone1 |  | text | 50 |
| LogisticPhone2 |  | text | 50 |
| LogisticTailLiftService |  | bool |  |
| LoseRemaining | Perdita residuo | bool |  |
| Mail | Mail | text | 100 |
| Markup | Ricarico | dec |  |
| MobilePhone | Telefono mobile | text | 50 |
| Name | Ragione sociale | text | 100 |
| Name2 | Ragione sociale 2 | text | 100 |
| [NickName](account.md#nickname) | Nickname | text | 100 |
| Notes | Note | text | text |
| OpeningDays | Giorni di apertura o chiusura | text | 30 |
| PaymentMethodId | Id del metodo di pagamento | text | 50 |
| PaymentTermId | Id del termine di pagamento | text | 50 |
| Phone | Telefono | text | 100 |
| Phone2 | Telefono | text | 50 |
| PriceListId | Id del listino associato al cliente | text | 50 |
| PriceListsReferenceDate | Data riferimento listini | date |  |
| ProcurementLeadTime | Tempo di approvvigionamento | int |  |
| ProspectId | Codice Prospect | text | 50 |
| RegistrationDocumentTypeId | Id del tipo di documento di registrazione | text | 50 |
| ResponsibleForTransportId | Id per il responsabile del trasporto | text | 50 |
| RetailPriceListId | Id del listino retail associato al cliente | text | 50 |
| SalesAgentId | Id dell'agente di riferimento | text | 50 |
| ShipmentMethodId | Id del metodo di consegna \(porto\) | text | 50 |
| StatisticClassId | Id della classe statistica | text | 50 |
| SyncReference | Riferimento | text | 50 |
| TotalFulfillment | Evasione integrale | bool |  |
| TransportModeId | Id del mezzo di trasporto | text | 50 |
| UniqueOfficeCode | Codice Univoco Ufficio | text | 50 |
| UploadToServerTimeStamp |  | dt |  |
| UseExceptionsPriceList | Indica se il cliente usa un listino eccezioni | bool |  |
| VatNumber | Partita Iva | text | 30 |
| VatRateId | Id dell'aliquota IVA | text | 50 |
| WarehouseId | Id del magazzino | text | 50 |
| ZoneId | Id della zona | text | 50 |

## AccountFilterId

questo campo è un valore sul quale possono essere filtrati i clienti in fase di ricerca. I valori utilizzati hanno un'anagrafica associata ovvero l'entità AccountFilter

## AccountTypeId

* 0: Undefined
* 1: Customer
* 2: ShipmentSite
* 3: Prospect

## ChargeForUnpackaged

* 0: No
* 1: Yes

## CreationReason

* 0: Undefined
* 1: AccountEdited
* 2: NewAccount
* 3: ProspectConvertedToCustomer

## CustomerTypeId

* 0: Undefined
* 1: Person
* 2: Organization

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

## Level

Non va più usato per identificare un account come prospect \(usare a tale scopo il campo 'AccountTypeId'\)..
* 0: Standard
* 1: SHOULD\_USE\_JUST\_FOR\_COMPATIBILITY\_Prospect
* 3: Bronze
* 4: Silver
* 5: Gold

## NickName

Nome usato 'comunemente' per indicare l'account, può essere differente dalla ragione sociale \(es. nome con cui è conosciuto un bar\)
