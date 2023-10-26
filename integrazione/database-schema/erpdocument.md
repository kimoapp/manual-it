---
description: Documenti da Erp
---

# ErpDocument

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
| AccountName | Ragione sociale del cliente | text | 100 |
| AccountName2 | Ragione sociale 2 del cliente | text | 100 |
| AccountNickName | Nickname cliente | text | 100 |
| AccountVatNumber | Partita Iva | text | 30 |
| AgreedAmount | Importo concordato | dec |  |
| Amount | Totale documento | dec |  |
| AmountIncludingVat | Totale documento incluso di IVA | dec |  |
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
| BillingAccountId | Id del cliente di fatturazione | text | 50 |
| BillingAccountIpaCode | Codice IPA | text | 20 |
| BillingAccountName | Ragione sociale del cliente di fatturazione | text | 100 |
| BillingAccountName2 | Ragione sociale 2 del cliente di fatturazione | text | 100 |
| BillingAccountNickName | Nickname cliente di fatturazione | text | 100 |
| BillingAccountVatNumber | Partita Iva | text | 30 |
| BudgetId | Id del budget da cui � stato creato il documento | text | 50 |
| BudgetLineId | Id della riga del budget da cui � stato creato il documento | text | 50 |
| CarrierId | Id del vettore | text | 50 |
| CigCode | Codice CIG | text | 50 |
| CupCode | Codice Cup | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerDiscountGroupId | Id del gruppo sconti cliente | text | 50 |
| CustomerGroupId | Id del gruppo cliente | text | 50 |
| CustomerPriceGroupId | Id del gruppo prezzo cliente | text | 50 |
| DeliveryDate | Data di consegna | date |  |
| DeliveryDateTypeId | Id del tipo consegna | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| DocumentDate | Data del documento | date |  |
| DocumentReference | Riferimento del documento | text | text |
| EndShipmentDate | Data di fine consegna | date |  |
| ErpDocumentTypeId | Id del tipo documento | text | 50 |
| ErpStatusId1 |  | text | 50 |
| ErpStatusId2 |  | text | 50 |
| ErpStatusId3 |  | text | 50 |
| ExpectedClosingDate |  | date |  |
| FixedDiscount | Sconto fisso | dec |  |
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
| FulfillmentDate | Data disponibilit� merce | date |  |
| [FulfillmentStatus](erpdocument.md#fulfillmentstatus) | Stato evasione documento | enum |  |
| GoodsAspectId | Id aspetto beni | text | 50 |
| Id | Id del documento | text | 50 |
| InvoiceDiscountId | Id sconto fattura | text | 50 |
| InvoiceDiscountValue | Importo sconto fattura | dec |  |
| Markup | Ricarico | dec |  |
| Notes | Note | text | text |
| Number | Numero documento | text | 50 |
| PaymentMethodDiscount1 | Sconto di pagamento legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount2 | Sconto di pagamento legato al metodo di pagamento | dec |  |
| PaymentMethodDiscount3 | Sconto di pagamento legato al metodo di pagamento | dec |  |
| PaymentMethodId | Id del metodo di pagamento | text | 50 |
| PriceListId | Id del listino | text | 50 |
| PricesReferenceDate | Data di riferimento dei prezzi | date |  |
| PrivateNotes | Note private | text | text |
| RecipientMail | Indirizzo Mail | text | n.d. |
| RegistrationDocumentTypeId | Id del tipo di documento di registrazione | text | 50 |
| ResponsibleForTransportId | Id del responsabile di trasporto | text | 50 |
| RetailPriceListId | Id del listino retail | text | 50 |
| SalesAgentId | Id dell'agente | text | 50 |
| SeasonId | Id della stagione | text | 50 |
| ShipmentMethodId | Id che identifica il metodo di pagamento | text | 50 |
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
| [ShipmentSite2Type](erpdocument.md#shipmentsite2type) | Tipo | enum |  |
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
| [ShipmentSiteType](erpdocument.md#shipmentsitetype) | Tipo | enum |  |
| SourceReference | Documento di origine | text | 50 |
| [SourceReferenceType](erpdocument.md#sourcereferencetype) |  | enum |  |
| StartShipmentDate | Data d'inizio della consegna | date |  |
| StatisticClassId | Id della classe statistica | text | 50 |
| TrademarkId | Id del marchio | text | 50 |
| TransportModeId | Id del mezzo di trasporto | text | 50 |
| VatAmount | Importo IVA | dec |  |
| VatRateId | Id | text | 50 |
| VatRateIsExemption | Indica se l'IVA è calcolata o no | bool |  |
| VatRateValue | Valore aliquota | dec |  |
| WarehouseId | Id del magazzino | text | 50 |
| ZoneId | Id della zona | text | 50 |

## FulfillmentStatus

* 0: Undefined
* 1: NotStarted
* 2: Partial
* 3: Completed
* 4: ForcedComplete

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
