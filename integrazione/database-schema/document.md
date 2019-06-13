---
description: null
---

# Document

  
 **Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountAddressCity | Città | text | 40 |
| AccountAddressCountry | Paese | text | 20 |
| AccountAddressCountrySubdivision | Provincia | text | 20 |
| AccountAddressLine | Indirizzo | text | 80 |
| AccountAddressPostCode | CAP | text | 20 |
| AccountCode | Codice cliente | text | 50 |
| AccountFiscalCode | Codice fiscale | text | 30 |
| AccountId | Id del cliente | text | 50 |
| AccountIpaCode | Codice IPA | text | 20 |
| AccountName | Ragione sociale cliente | text | 100 |
| AccountName2 | Ragione sociale 2 cliente | text | 100 |
| AccountNickName | Nickname cliente | text | 100 |
| AccountVatNumber | Partita Iva | text | 30 |
| AgreedAmount | Importo concordato | dec |  |
| Amount | Totale documento | dec |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |
| [AppOrigin](document.md#apporigin) | Codice CIG | enum |  |
| ArchivingNotes | Note per il motivo di archiviazione | text | text |
| ArchivingReasonId | Id della causale di archiviazione | text | 50 |
| AvailabilityRuleId | Id della regola di disponibilità | text | 50 |
| BankAbi | Codice ABI | text | 5 |
| BankCab | Codice CAB | text | 5 |
| BankCc | Codice CC | text | 20 |
| BankCin | Codice CIN | text | 1 |
| BankIban | Codice IBAN | text | 50 |
| BankShouldRegisterOnErp | Indica se il conto corrente va registro nell'Erp | bool |  |
| BillingAccountAddressCity | Città | text | 40 |
| BillingAccountAddressCountry | Paese | text | 20 |
| BillingAccountAddressCountrySubdivision | Provincia | text | 20 |
| BillingAccountAddressLine | Indirizzo | text | 80 |
| BillingAccountAddressPostCode | CAP | text | 20 |
| BillingAccountCode | Codice cliente di fatturazione | text | 50 |
| BillingAccountFiscalCode | Codice fiscale | text | 30 |
| BillingAccountId | Id cliente di fatturazione | text | 50 |
| BillingAccountIpaCode | Codice IPA | text | 20 |
| BillingAccountName | Nome cliente di fatturazione | text | 100 |
| BillingAccountName2 | Nome 2 cliente di fatturazione | text | 100 |
| BillingAccountNickName | Nickname cliente di fatturazione | text | 100 |
| BillingAccountVatNumber | Partita Iva | text | 30 |
| CarrierId | Id del vettore | text | 50 |
| CigCode | Codice CIG | text | 50 |
| CollectOnSite |  | bool |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| CupCode | Codice Cup | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerDiscountGroupId | Id del gruppo sconti cliente | text | 50 |
| CustomerPriceGroupId | Id del gruppo prezzo cliente | text | 50 |
| DeliveryDate | Data consegna | date |  |
| DeliveryDateTypeId | Tipo data consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| DiscountOverRetailAmount | Sconto su imponibile retail | dec |  |
| DiscountOverRetailAmountIncludingVat | Sconto su importo retail IVA compresa | dec |  |
| DocumentDate | Data documento | date |  |
| [DocumentFamilyId](document.md#documentfamilyid) | Id della famiglia documento | enum |  |
| DocumentMarkup | Ricarico | dec |  |
| DocumentMarkupOnNetCost | Margine | dec |  |
| DocumentReference | Documento di riferimento | text | text |
| [DocumentStatus](document.md#documentstatus) | Stato del documento | enum |  |
| DocumentTypeId | Id del tipo documento | text | 50 |
| EndShipmentDate | Fine data spedizione | date |  |
| [EntityStatus](document.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ExpectedClosingDate |  | date |  |
| FixedDiscount | Sconto importo | dec |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeBoolean4 | Campo booleano libero | bool |  |
| FreeBoolean5 | Campo booleano libero | bool |  |
| FreeBoolean6 | Campo booleano libero | bool |  |
| FreeBoolean7 | Campo booleano libero | bool |  |
| FreeDateTime1 | Campo data libero | dt |  |
| FreeDateTime2 | Campo data libero | dt |  |
| FreeDateTime3 | Campo data libero | dt |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeDecimal4 | Campo decimale libero | dec |  |
| FreeDecimal5 | Campo decimale libero | dec |  |
| FreeLookup1 | Id per dati tabellati | text | 50 |
| FreeLookup2 | Id per dati tabellati | text | 50 |
| FreeLookup3 | Id per dati tabellati | text | 50 |
| FreeLookup4 | Id per dati tabellati | text | 50 |
| FreeLookup5 | Id per dati tabellati | text | 50 |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| FreeText4 | Campo testo libero | text | text |
| FreeText5 | Campo testo libero | text | text |
| GoodsAspectId | Id aspetto beni | text | 50 |
| Id | Id | text | 50 |
| InvoiceDiscountId | Id sconto fattura | text | 50 |
| InvoiceDiscountValue | Importo sconto fattura | dec |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| IsFatturaPA | Indica se il documento è una FatturaPA | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| LineDiscount1 | Sconto per riga | dec |  |
| LineDiscount2 | Sconto per riga | dec |  |
| LineDiscount3 | Sconto per riga | dec |  |
| LineDiscount4 | Sconto per riga | dec |  |
| LineDiscount5 | Sconto per riga | dec |  |
| LogisticCallRequest |  | bool |  |
| LogisticDeliveryToFloor |  | bool |  |
| LogisticLimitedTrafficZone |  | bool |  |
| LogisticNotes |  | text | text |
| LogisticOpeningDays |  | text | 30 |
| LogisticOpeningTimes |  | text | 50 |
| LogisticPhone1 |  | text | 50 |
| LogisticPhone2 |  | text | 50 |
| LogisticTailLiftService |  | bool |  |
| Markup | Ricarico | dec |  |
| Notes | Note | text | text |
| Number | Numero documento | text | 50 |
| NumbersRegistryId | Id del numero registrazione | text | 50 |
| PaymentMethodDiscount1 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount2 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount3 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodId | Id del metodo di pagamento | text | 50 |
| PointsPerSale | Punti per la vendita | dec |  |
| Prebuy | Gestione 'prebuy' | bool |  |
| PriceListId | Id del listino | text | 50 |
| PricesReferenceDate | Data di riferimento per i prezzi | date |  |
| PrivateNotes | Note private | text | text |
| RegistrationDocumentTypeId | Id del tipo documento di registrazione | text | 50 |
| ReportRecipients |  | text | text |
| ResponsibleForTransportId | Id del responsabile di trasporto | text | 50 |
| RetailAmount | Totale documento | dec |  |
| RetailAmountIncludingVat | Totale documento incluso di IVA | dec |  |
| RetailPriceListId | Id del listino retail | text | 50 |
| SeasonGroupId | Id del gruppo stagioni | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| ShipmentDescription | Descrizione spedizione | text | text |
| ShipmentMethodId | Id del metodo di spedizione \(porto\) | text | 50 |
| ShipmentSiteAddressCity | Città | text | 40 |
| ShipmentSiteAddressCountry | Paese | text | 20 |
| ShipmentSiteAddressCountrySubdivision | Provincia | text | 20 |
| ShipmentSiteAddressLine | Indirizzo | text | 80 |
| ShipmentSiteAddressPostCode | CAP | text | 20 |
| ShipmentSiteCode | Codice | text | 50 |
| ShipmentSiteFax | Fax | text | 50 |
| ShipmentSiteId | Id | text | 50 |
| ShipmentSiteMail | Mail | text | 100 |
| ShipmentSiteMobilePhone | Telefono mobile | text | 50 |
| ShipmentSiteName | Nome | text | 100 |
| ShipmentSiteName2 | Nome 2 | text | 100 |
| ShipmentSitePhone | Telefono | text | 100 |
| ShipmentSiteShouldRegisterOnErp | Indica se la destinazione merci va registra nell'Erp | bool |  |
| ShippingChargesAmount | Spese di spedizione | dec |  |
| ShippingChargesVatRateId | Aliquota IVA per le spese di spedizione | text | 50 |
| SourceReference | Documento di origine | text | 50 |
| [SourceReferenceType](document.md#sourcereferencetype) |  | enum |  |
| StartShipmentDate | Data inizio spedizione | date |  |
| SyncReference | Riferimento | text | 50 |
| TotalAverageDiscount | Sconto medio totale | dec |  |
| TrademarkId | Id del marchio | text | 50 |
| TransportModeId | Id del mezzo di trasporto | text | 50 |
| UploadToServerTimeStamp |  | dt |  |
| VatAmount | Importo IVA | dec |  |
| VatRateId | Id | text | 50 |
| VatRateIsExemption | Indica se l'IVA è calcolata o no | bool |  |
| VatRateValue | Valore aliquota | dec |  |
| WarehouseId | Id del magazzino | text | 50 |

## AppOrigin

0: Undefined  
1: B2b

## DocumentFamilyId

1: SalesOrders  
2: SalesQuotes  
3: SalesInvoices  
4: NoteCredito  
5: DDT  
6: Inventories  
7: WorkSessions

## DocumentStatus

0: Open  
1: Confirmed  
2: SalesQuoteTransformedToOrder  
3: Archived

## EntityStatus

0: ImportedFromErp  
1: ExportedToErp  
2: ImportedByErp  
3: ExportingToErp  
4: Deleted  
5: CommittingExportToErp  
6: ToExportToErp  
7: Editing  
8: UploadedToServer  
10: EditingPending

## SourceReferenceType

0: Undefined  
1: FromSalesQuote  
2: Budget

