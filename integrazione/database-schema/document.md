---
description: 
---

# Document

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountAddressCity | Città | text | 40 |
| AccountAddressCountry | Paese | text | 20 |
| AccountAddressCountrySubdivision | Provincia | text | 20 |
| AccountAddressLine | Indirizzo | text | 200 |
| AccountAddressPostCode | CAP | text | 20 |
| AccountFiscalCode | Codice fiscale | text | 30 |
| AccountId | Id del cliente | text | 50 |
| AccountIpaCode | Codice IPA | text | 20 |
| AccountName | Ragione sociale cliente | text | 100 |
| AccountName2 | Ragione sociale 2 cliente | text | 100 |
| AccountNickName | Nickname cliente | text | 100 |
| AccountVatNumber | Partita Iva | text | 30 |
| AgreedAmount | Importo concordato | dec |  |
| AlternativeNumber | Numero dell'alternativà | text | 50 |
| AlternativesAggregationId | Id dell'aggregato di riferimento del documento | text | 50 |
| Amount | Totale documento | dec |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |
| [AppOrigin](document.md#apporigin) | App da cui è stato generato il documento | enum |  |
| ArchivingNotes | Note per il motivo di archiviazione | text | text |
| ArchivingReasonId | Id della causale di archiviazione | text | 50 |
| AvailabilityRuleId | Id della regola di disponibilità | text | 50 |
| BankAbi | Codice ABI | text | 5 |
| BankCab | Codice CAB | text | 5 |
| BankCc | Codice CC | text | 20 |
| BankCin | Codice CIN | text | 1 |
| BankCountryCode | Codice del paese | text | 5 |
| BankIban | Codice IBAN | text | 50 |
| BankIbanCheckDigits | Check digits dell'IBAN | text | 5 |
| BankShouldRegisterOnErp | Indica se il conto corrente va registro nell'Erp | bool |  |
| BillingAccountAddressCity | Città | text | 40 |
| BillingAccountAddressCountry | Paese | text | 20 |
| BillingAccountAddressCountrySubdivision | Provincia | text | 20 |
| BillingAccountAddressLine | Indirizzo | text | 200 |
| BillingAccountAddressPostCode | CAP | text | 20 |
| BillingAccountFiscalCode | Codice fiscale | text | 30 |
| BillingAccountId | Id cliente di fatturazione | text | 50 |
| BillingAccountIpaCode | Codice IPA | text | 20 |
| BillingAccountName | Nome cliente di fatturazione | text | 100 |
| BillingAccountName2 | Nome 2 cliente di fatturazione | text | 100 |
| BillingAccountNickName | Nickname cliente di fatturazione | text | 100 |
| BillingAccountVatNumber | Partita Iva | text | 30 |
| BudgetId | Id del budget da cui è stato creato il documento | text | 50 |
| BudgetLineId | Id della riga del budget da cui è stato creato il documento | text | 50 |
| CarrierId | Id del vettore | text | 50 |
| [ChargeForUnpackaged](document.md#chargeforunpackaged) | Addebita fuori confezione \(sfusi\) | enum |  |
| CigCode | Codice CIG | text | 50 |
| CollectOnSite | Ritiro in sede \(al banco\) della merce | bool |  |
| CollectOnSiteDateTime | Data/ora del ritiro della merce | date |  |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| CupCode | Codice Cup | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerDiscountGroupId | Id del gruppo sconti cliente | text | 50 |
| CustomerGroupId | Id del gruppo cliente | text | 50 |
| CustomerPriceGroupId | Id del gruppo prezzo cliente | text | 50 |
| DeliveryDate | Data consegna | date |  |
| DeliveryDateTypeId | Tipo data consegna | text | 50 |
| DeliveryRouteDays | Giorni di consegna | text | 50 |
| DeliveryRouteFrequency | Frequenza delle consegne | text | 50 |
| DeliveryRouteId | Id del giro di consegna | text | 50 |
| DeliveryRouteTimes | Orari di consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| DiscountOverRetailAmount | Sconto su imponibile retail | dec |  |
| DiscountOverRetailAmountIncludingVat | Sconto su importo retail IVA compresa | dec |  |
| DocumentConfirmationTimeStamp | Data conferma documento | date |  |
| DocumentDate | Data documento | date |  |
| [DocumentFamilyId](document.md#documentfamilyid) | Id della famiglia documento | enum |  |
| DocumentLineGroups | Raggruppamento righe nel documento | text | text |
| DocumentMarkup | Ricarico percentuale | dec |  |
| DocumentMarkupAmount | Ricarico in valore | dec |  |
| DocumentReference | Documento di riferimento | text | text |
| DocumentSaleMargin | Margine percentuale | dec |  |
| DocumentSaleMarginAmount | Margine in valore | dec |  |
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
| FulfillmentDate | Data evadibilità | date |  |
| FulfillmentStatus | Stato evadibilità | enum |  |
| GoodsAspectId | Id aspetto beni | text | 50 |
| Id | Id | text | 50 |
| InvoiceDiscountId | Id sconto fattura | text | 50 |
| InvoiceDiscountValue | Importo sconto fattura | dec |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| IsFatturaPA | Indica se il documento è una FatturaPA | bool |  |
| ItemCollectionId | Id della collezione | text | 50 |
| ItemLineId | Id della line articolo | text | 50 |
| ItemSeriesId | Id della serie articolo | text | 50 |
| LanguageId | Id della lingua di riferimento del documento | text | 20 |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| LegalNoticeAcceptance | Accettazione 'clausole vessatorie' | bool |  |
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
| LoseRemaining | Perdita residuo | bool |  |
| Markup | Ricarico | dec |  |
| Notes | Note | text | text |
| Number | Numero documento | text | 50 |
| NumbersRegistryId | Id del numero registrazione | text | 50 |
| OpportunityId | Id opportunità di riferimento del documento | text | 50 |
| PaidAmount | Importo incassato | dec |  |
| PaymentForcedlyClosed | Pagamento chiuso forzatamente | bool |  |
| PaymentMethodDiscount1 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount2 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount3 | Sconto legato al metodo di pagamento | dec |  |
| PaymentMethodId | Id del metodo di pagamento | text | 50 |
| PaymentTermDiscount1 | Sconto di pagamento legato al termine di pagamento | dec |  |
| PaymentTermDiscount2 | Sconto di pagamento legato al termine di pagamento | dec |  |
| PaymentTermDiscount3 | Sconto di pagamento legato al termine di pagamento | dec |  |
| PaymentTermId | Id del termine di pagamento | text | 50 |
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
| ReviewerId | Id dell'utente che ha effettuato la review \(documento approvato/rifiutato\) | text | 50 |
| ReviewTimeStamp | Data/ora della review | dt |  |
| SalesTermsAcceptance | Accettazione 'condizioni generali di vendita' | bool |  |
| SeasonGroupId | Id del gruppo stagioni | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| ShipmentDescription | Descrizione spedizione | text | text |
| ShipmentMethodId | Id del metodo di spedizione \(porto\) | text | 50 |
| ShipmentSite2AddressCity | Città | text | 40 |
| ShipmentSite2AddressCountry | Paese | text | 20 |
| ShipmentSite2AddressCountrySubdivision | Provincia | text | 20 |
| ShipmentSite2AddressLine | Indirizzo | text | 200 |
| ShipmentSite2AddressPostCode | CAP | text | 20 |
| ShipmentSite2Fax | Fax | text | 50 |
| ShipmentSite2Id | Id | text | 50 |
| ShipmentSite2Mail | Mail | text | 100 |
| ShipmentSite2MobilePhone | Telefono mobile | text | 50 |
| ShipmentSite2Name | Nome | text | 100 |
| ShipmentSite2Name2 | Nome 2 | text | 100 |
| ShipmentSite2Phone | Telefono | text | 100 |
| ShipmentSite2ShouldRegisterOnErp | Indica se la destinazione merci va registra nell'Erp | bool |  |
| [ShipmentSite2Type](document.md#shipmentsite2type) | Tipo | enum |  |
| ShipmentSiteAddressCity | Città | text | 40 |
| ShipmentSiteAddressCountry | Paese | text | 20 |
| ShipmentSiteAddressCountrySubdivision | Provincia | text | 20 |
| ShipmentSiteAddressLine | Indirizzo | text | 200 |
| ShipmentSiteAddressPostCode | CAP | text | 20 |
| ShipmentSiteFax | Fax | text | 50 |
| ShipmentSiteId | Id | text | 50 |
| ShipmentSiteMail | Mail | text | 100 |
| ShipmentSiteMobilePhone | Telefono mobile | text | 50 |
| ShipmentSiteName | Nome | text | 100 |
| ShipmentSiteName2 | Nome 2 | text | 100 |
| ShipmentSitePhone | Telefono | text | 100 |
| ShipmentSiteShouldRegisterOnErp | Indica se la destinazione merci va registra nell'Erp | bool |  |
| [ShipmentSiteType](document.md#shipmentsitetype) | Tipo | enum |  |
| ShippingChargesAmount | Spese di spedizione | dec |  |
| ShippingChargesVatRateId | Aliquota IVA per le spese di spedizione | text | 50 |
| SourceReference | Documento di origine | text | 50 |
| [SourceReferenceType](document.md#sourcereferencetype) |  | enum |  |
| StartShipmentDate | Data inizio spedizione | date |  |
| SyncReference | Riferimento | text | 50 |
| TotalAverageDiscount | Sconto medio totale | dec |  |
| TotalFulfillment | Evasione integrale | bool |  |
| TotalVolume | Totale volume del documento | dec |  |
| TotalWeight | Totale peso del documento | dec |  |
| TrademarkId | Id del marchio | text | 50 |
| TransportModeId | Id del mezzo di trasporto | text | 50 |
| UploadToServerTimeStamp |  | dt |  |
| VatAmount | Importo IVA | dec |  |
| VatRateId | Id | text | 50 |
| VatRateIsExemption | Indica se l'IVA è calcolata o no | bool |  |
| VatRateValue | Valore aliquota | dec |  |
| WarehouseId | Id del magazzino | text | 50 |

## AppOrigin

* 0: Undefined
* 1: B2b

## ChargeForUnpackaged

* 0: No
* 1: Yes

## DocumentFamilyId

* 0: Undefined
* 1: SalesOrders
* 2: SalesQuotes
* 3: SalesInvoices
* 4: NoteCredito
* 5: DeliveryNotes
* 6: Inventories
* 7: WorkSessions

## DocumentStatus

* 0: Open
* 1: Confirmed
* 2: SalesQuoteTransformedToOrder
* 3: Archived
* 4: ApprovalByManagerRequired
* 5: ApprovalByAccountRequired
* 6: RejectedByAccount
* -1: Undefined

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

## ShipmentSite2Type

* 0: Account
* 1: Warehouse

## ShipmentSiteType

* 0: Account
* 1: Warehouse

## SourceReferenceType

* 0: Undefined
* 1: FromSalesQuote
* 2: Budget
* 3: FromCart
* 4: FromAppCopriwaterGiusto
* 5: ErpDocument
