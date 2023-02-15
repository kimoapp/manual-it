# Document Data Model



### Report

| Campo                   | Tipo                                                                                     | Descrizione                                                                    |
| ----------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| ReportType              | [ReportType](document-data-model.md#reporttype)                                          | Tipo di report generato                                                        |
| ReportDate              | DateTime                                                                                 | Data di generazione del report                                                 |
| User                    | [User](./#user)                                                                          | Utente che ha richiesto il report                                              |
| SalesAgent              | [SalesAgent](../../integrazione/database-schema/salesagent.md)                           | Agente associato all'utente che ha richiesto il report                         |
| Account                 | [AccountReport](document-data-model.md#accountreport)                                    | Cliente associato al documento su cui è stato generato il report               |
| ShipmentSite            | [AccountReport](document-data-model.md#accountreport)                                    | Destinazione merci associata al documento su cui è stato generato il report    |
| Document                | [DocumentHeaderReport](document-data-model.md#header)                                    | Informazioni sulla testata del documento                                       |
| Line                    | [DocumentLineReport](document-data-model.md#line)                                        | Informazioni sulle righe del documento                                         |
| Item                    | [ItemReport](document-data-model.md#itemreport)                                          | Informazioni legate agli articoli di ogni riga del documento                   |
| Variable1               | [VariableValue](../../integrazione/database-schema/variablevalue.md)                     | Variante 1                                                                     |
| DocumentType            | [DocumentType](document-data-model.md#documenttype)                                      | Tipo di documento                                                              |
| Currency                | [Currency](../../integrazione/database-schema/currency.md)                               | Valuta                                                                         |
| Trademark               | [Trademark](../../integrazione/database-schema/trademark.md)                             | Marchio                                                                        |
| Season                  | [Season](../../integrazione/database-schema/season.md)                                   | Stagione                                                                       |
| PaymentMethod           | [PaymentMethod](../../integrazione/database-schema/paymentmethod.md)                     | Metodo di pagamento utilizzato nel documento                                   |
| ShipmentMethod          | [ShipmentMethod](../../integrazione/database-schema/shipmentmethod.md)                   | Metodo di spedizione utilizzato nel documento                                  |
| FreeLookup1             | [FreeLookup](../../integrazione/database-schema/freelookup.md)                           |                                                                                |
| FreeLookup2             | [FreeLookup](../freelookup.md)                                                           |                                                                                |
| Variables               | IEnumerable<[VarInfo](document-data-model.md#varinfo)>                                   | Informazioni sulle varianti degli articoli presenti tra le linee del documento |
| ImagePath               | string                                                                                   | Percorso del file immagine di ciascun articolo                                 |
| GroupByField            | string                                                                                   | Campo da utilizzare nei raggruppamenti                                         |
| ResponsibleForTransport | [ResponsibleForTransport](../../integrazione/database-schema/responsiblefortransport.md) | Responsabile del trasporto                                                     |
| TransportMode           | [TransportMode](../../integrazione/database-schema/transportmode.md)                     | Metodo di trasporto                                                            |

### DocumentType

| Campo                                      | Tipo                                                         | Descrizione                                                       |
| ------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------------------------- |
| Id                                         | string                                                       | Id del tipo documento su Kimo                                     |
| Code                                       | string                                                       | Id del tipo documento utilizzato nel gestionale                   |
| DocumentFamilyId                           | [DocumentFamilyId](document-data-model.md#document-familyid) | Famigli di appartenenza del documento                             |
| PluralDescription                          | string                                                       | Descrizione del tipo documento al plurale                         |
| SingularDescription                        | string                                                       | Descrizione del tipo documento al singolare                       |
| NumberTemplate                             | string                                                       |                                                                   |
| SortPriority                               | int                                                          | Priorità di ordinamento                                           |
| PriceListId                                | string                                                       | Codice del listino prezzi                                         |
| ValidityRange                              | ValidityRange                                                | Date del range di validità                                        |
| DefaultDeliveryDate                        | DateTime                                                     | Data di consegna di default                                       |
| CanCreateForRegularAccounts                | bool                                                         | Può essere creato peri Clienti regolari                           |
| CanCreateForLockedAccounts                 | bool                                                         | Può essere creato per i Clienti bloccati                          |
| CanCreateForNewCustomers                   | bool                                                         | Può essere creato per i nuovi Clienti                             |
| CanCreateForNewShipmentSites               | bool                                                         | Può essere creato per le nuove destinazioni merci                 |
| CanCreateForProspects                      | bool                                                         | Può essere creato per i potenziali Clienti                        |
| CanSendToErp                               | bool                                                         | Può essere inviato all'Erp                                        |
| ShouldExportDraftsToErp                    | bool                                                         | Deve essere esportata una bozza all'Erp                           |
| DaysForExpectedClosing                     | int                                                          | Giorni attesi per la chiusura                                     |
| ShouldHandleExpectedClosingDateOnDocuments | bool                                                         | Deve essere gestita la chiusura del documento dopo la data attesa |

### ValidityRange

| Campo     | Tipo     | Descrizione  |
| --------- | -------- | ------------ |
| StartDate | DateTime | Data inizio  |
| EndDate   | DateTime | Data fine    |

### VarInfo

| Campo         | Tipo    | Description         |
| ------------- | ------- | ------------------- |
| Id            | string  | Codice articolo     |
| ValueId       | string  | Codice variante     |
| Description   | string  | Descrizione         |
| SalesQty      | decimal | Quantità di vendita |
| NumberOfPacks | decimal | Numero confezioni   |
| Amount        | decimal | Totale              |

### User

| Campo            | Tipo                                                                | Valore                                                                                                  |
| ---------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Id               | string                                                              | Codice dell'utente in Kimo                                                                              |
| SalesAgentId     | string                                                              | Codice dell'agente associato all'utente Kimo                                                            |
| UserType         | [UserType](document-data-model.md#usertype)                         | Tipo di utente                                                                                          |
| CompanyId        | string                                                              | Codice dell'Azienda                                                                                     |
| Username         | string                                                              | Nome utente                                                                                             |
| FirstName        | string                                                              | Nome                                                                                                    |
| LastName         | string                                                              | Cognome                                                                                                 |
| FullName         | string                                                              | Nome e Cognome                                                                                          |
| ProfileName      | string                                                              |                                                                                                         |
| Mail             | string                                                              |                                                                                                         |
| UseAsMailSender  | bool                                                                | L'indirizzo dell'utente deve essere utilizzato come mittente                                            |
| BccMyself        | bool                                                                | Aggiungi l'indirizzo dell'utente in Bcc nei report inviati                                              |
| ReportMails      | string                                                              | Indirizzi aggiuntivi a cui inviare il report senza che siano specificati nell'apposito campo ogni volta |
| ReportMailsUsage | [UserReportMailsUsage](document-data-model.md#userreportmailsusage) | Metodo di invio mail agli indirizzi destinatari aggiuntivi                                              |
| WarehouseId      | string                                                              | Codice del magazzino                                                                                    |
| Series           | string                                                              |                                                                                                         |
| CustomerId       | string                                                              | Codice del cliente                                                                                      |
| UiLanguageId     | string                                                              | Codice della lingua                                                                                     |

### ReportType

| Campo        | Tipo   | Description                                                                                                                                                                                  |
| ------------ | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Id           | string | Codice del tipo report in Kimo                                                                                                                                                               |
| Code         | string | Codice del tipo report lato Erp                                                                                                                                                              |
| Description  | string |                                                                                                                                                                                              |
| TemplateName | string | Nome del file utilizzato come teplate                                                                                                                                                        |
| Context      | string | Contesto di dati gestiti nella generazione del report, l'unico supportato al momento è Document                                                                                              |
| SortPriority | string | Priorità di ordinamento dei tipi di report                                                                                                                                                   |
| PrintMode    | string | Metodo di stampa report. I possibili valori cono empty, VariableItem (per articoli gestiti a varianti), GroupedByManufacturer (Linee del documento raggruppate per il codice del produttore) |

### AccountReport

| Campo        | Tipo   | Descrizione                |
| ------------ | ------ | -------------------------- |
| Id           | String | Codice del cliente         |
| Fax          | String |                            |
| Phone        | String |                            |
| VatNumber    | String | Partita IVA del cliente    |
| FiscalCod    | String | Codice fiscale del cliente |
| Mail         | String |                            |
| FreeText1..5 | String | Campi testuali liberi      |

### ItemReport

| Campo                  | Tipo                                        | Descrizione                                            |
| ---------------------- | ------------------------------------------- | ------------------------------------------------------ |
| ItemDiscountGroupId    | string                                      | Gruppo sconti articolo                                 |
| ItemSeriesId           | string                                      | Codice della serie associata all'articolo              |
| CollectionId           | string                                      | Codice della collezione                                |
| LineId                 | string                                      | Id della linea documento                               |
| TrademarkId            | string                                      | Codice marca dell'articolo                             |
| SeasonId               | string                                      | Codice della stagione                                  |
| VatRateId              | string                                      |                                                        |
| Notes                  | string                                      |                                                        |
| EndCustomerPrice       | decimal                                     | Prezzo al cliente finale                               |
| BaseSalesUomId         | string                                      |                                                        |
| ItemType               | [ItemType](document-data-model.md#itemtype) | Tipo articolo                                          |
| Description            | string                                      |                                                        |
| LongDescription        | string                                      | Descrizione estesa                                     |
| ManufacturerId         | string                                      | Codice del produttore                                  |
| ManufacturerItemId     | string                                      | Codice del articolo produttore                         |
| ItemGroupLevel1Id      | string                                      | Gruppo merceologico livello 1                          |
| ItemGroupLevel2Id      | string                                      | Gruppo merceologico livello 2                          |
| ItemGroupLevel3Id      | string                                      | Gruppo merceologico livello 3                          |
| ItemGroupLevel4Id      | string                                      | Gruppo merceologico livello 4                          |
| FreeText1..3           | string                                      | Campi testuali liberi                                  |
| FreeDecimal1..3        | decimal                                     | Campi decimali liberi                                  |
| FreeBoolean1..5        | bool                                        | Campi booleani liberi                                  |
| ChannelsEnabled        | ChannelType                                 | Canale/Canali in cui risulta visualizzabile l'articolo |
| IsVisibleOnItemsSearch | bool                                        | È possibile visualizzare l'articolo nel catalogo SFA   |
| Prebuy                 | bool                                        |                                                        |

### **Header**

| Campo                                   | Tipo                                                         | Description                                   |
| --------------------------------------- | ------------------------------------------------------------ | --------------------------------------------- |
| Id                                      | string                                                       | Codice documento                              |
| DocumentFamilyId                        | [DocumentFamilyId](document-data-model.md#document-familyid) | Famiglia di appartenenza del documento        |
| DocumentTypeId                          | string                                                       | Codice del tipo documento                     |
| NumbersRegistryId                       | string                                                       | Codice del registro numeratore                |
| Number                                  | string                                                       | Numero documento                              |
| DocumentDate                            | DateTime                                                     | Data documento                                |
| CreationDate                            | DateTime                                                     | Data creazione documento                      |
| DeliveryDate                            | DateTime                                                     | Data prevista consegna                        |
| DeliveryDateTypeId                      | string                                                       | Tipo data consegna                            |
| StartShipmentDate                       | DateTime                                                     | Data inizio range prevista consegna           |
| EndShipmentDate                         | DateTime                                                     | Data fine range prevista consegna             |
| ReportRecipient                         | string                                                       | Indirizzi destinatari del report              |
| AccountId                               | string                                                       | Codice cliente su Kimo                        |
| AccountCode                             | string                                                       | Codice cliente Erp                            |
| AccountFullName                         | string                                                       | Nome completo del cliente                     |
| AccountName                             | string                                                       | Nome Cliente                                  |
| AccountName2                            | string                                                       | Nome aggiuntivo del cliente                   |
| AccountNickName                         | string                                                       | Soprannome cliente                            |
| AccountAddressLine                      | string                                                       | Indirizzo cliente                             |
| AccountAddressCity                      | string                                                       | Città del cliente                             |
| AccountAddressPostCode                  | string                                                       | Codice postale del cliente                    |
| AccountAddressCountrySubdivision        | string                                                       | Provincia indirizzo cliente                   |
| AccountAddressCountry                   | string                                                       | Nazione indirizzo cliente                     |
| AccountVatNumber                        | string                                                       | Partita IVA cliente                           |
| AccountFiscalCode                       | string                                                       | Codice fiscale cliente                        |
| BillingAccountId                        | string                                                       | Codice cliente di fatturazione                |
| BillingAccountFullName                  | string                                                       | Nome completo cliente di fatturazione         |
| BillingAccountName                      | string                                                       | Nome cliente di fatturazione                  |
| BillingAccountName2                     | string                                                       | Nome aggiuntivo cliente di fatturazione       |
| BillingAccountNickName                  | string                                                       | Nickname cliente di fatturazione              |
| BillingAccountAddressLine               | string                                                       | Indirizzo cliente di fatturazione             |
| BillingAccountAddressCity               | string                                                       | Città cliente di fatturazione                 |
| BillingAccountAddressPostCode           | string                                                       | Codice postale cliente di fatturazione        |
| BillingAccountAddressCountrySubdivision | string                                                       | Provincia cliente di fatturazione             |
| BillingAccountAddressCountry            | string                                                       | Nazione cliente di fatturazione               |
| BillingAccountVatNumber                 | string                                                       | Partita IVA cliente di fatturazione           |
| BillingAccountFiscalCode                | string                                                       | Codice fiscale cliente di fatturazione        |
| ShipmentSiteId                          | string                                                       | Codice destinazione merci su Kimo             |
| ShipmentSiteCode                        | string                                                       | Codice destinazione merci nell'Erp            |
| ShipmentSiteFullName                    | string                                                       | Nome completo destinazione merci              |
| ShipmentSiteName                        | string                                                       | Nome della destinazione merci                 |
| ShipmentSiteName2                       | string                                                       | Nome aggiuntivo della destinazione merci      |
| ShipmentSiteAddressLine                 | string                                                       | Indirizzo destinazione merci                  |
| ShipmentSiteAddressCity                 | string                                                       | Città indirizzo destinazione merci            |
| ShipmentSiteAddressPostCode             | string                                                       | Codice postale indirizzo destinazione merci   |
| ShipmentSiteAddressCountrySubdivision   | string                                                       | Provincia indirizzo destinazione merci        |
| ShipmentSiteAddressCountry              | string                                                       | Nazione destinazione merci                    |
| BankAbi                                 | string                                                       |                                               |
| BankCab                                 | string                                                       |                                               |
| BankCc                                  | string                                                       |                                               |
| BankCin                                 | string                                                       |                                               |
| BankIban                                | string                                                       |                                               |
| TrademarkId                             | string                                                       | Codice della marca                            |
| SeasonId                                | string                                                       | Codice della stagione                         |
| AvailabilityRuleId                      | string                                                       | Regola da applicare alle disponibilità        |
| WarehouseId                             | string                                                       | Codice magazzino                              |
| CollectOnSite                           | bool                                                         |                                               |
| PriceListId                             | string                                                       | Codice del listino prezzi                     |
| CurrencyId                              | string                                                       | Valuta                                        |
| PaymentMethodId                         | string                                                       | Codice del metodo di pagamento                |
| RegistrationDocumentTypeId              | string                                                       |                                               |
| CarrierId                               | string                                                       |                                               |
| ResponsibleForTransportId               | string                                                       | Responsabile al trasporto                     |
| GoodsAspectId                           | string                                                       |                                               |
| ShipmentMethodId                        | string                                                       | Codice metodo di trasporto                    |
| TransportModeId                         | string                                                       | Codice modalità di trasporto                  |
| FixedDiscount                           | decimal                                                      |                                               |
| Markup                                  | decimal                                                      |                                               |
| InvoiceDiscountId                       | string                                                       |                                               |
| InvoiceDiscountValue                    | decimal                                                      |                                               |
| DocumentReference                       | string                                                       |                                               |
| VatRateId                               | string                                                       | Codice IVA                                    |
| VatRateValue                            | decimal                                                      | Valore IVA                                    |
| VatRateIsExemption                      | bool                                                         | Esente da IVA                                 |
| Notes                                   | string                                                       |                                               |
| PrivateNotes                            | string                                                       |                                               |
| AmountWithoutInvoiceDiscount            | decimal                                                      | Totale senza sconti                           |
| Amount                                  | decimal                                                      | Totale                                        |
| VatAmount                               | decimal                                                      | Totale IVA                                    |
| AmountIncludingVat                      | decimal                                                      | Totale IVA compresa                           |
| CreatorId                               | string                                                       | Codice dell'Agente che ha creato il documento |
| ExportToErpTimeStamp                    | DateTime                                                     | Orario di export all'Erp                      |
| UploadToServerTimeStamp                 | DateTime                                                     | Orario di caricamento sul server              |
| FreeText1..3                            | string                                                       | Campi testuali liberi                         |
| ShipmentDescription                     | string                                                       |                                               |
| PointsPerSale                           | decimal                                                      | Punti per la vendita                          |
| TotalAverageDiscount                    | decimal                                                      | Sconto medio totale                           |
| DocumentMarkupOnNetCost                 | decimal                                                      | Ricarico sul costo netto                      |
| DocumentMarkup                          | decimal                                                      | Ricarico documento                            |
| DiscountOverRetailAmountIncludingVat    | decimal                                                      | Sconto sul prezzo commerciale IVA compresa    |
| DiscountOverRetailAmount                | decimal                                                      | Sconto sul prezzo commerciale                 |

****

### Line

| Campo                         | Tipo                                                        | Descrizione                                                                                |
| ----------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Id                            | string                                                      | Codice della linea                                                                         |
| DocumentId                    | string                                                      | Coduce del documento di riferimento                                                        |
| LineNumber                    | int                                                         | Numero linea                                                                               |
| LineType                      | [DocumentLineType](document-data-model.md#documentlinetype) | Tipo di linea                                                                              |
| ItemId                        | string                                                      | Codice articolo                                                                            |
| ItemDescription               | string                                                      | Descrizione articolo                                                                       |
| ManufacturerId                | string                                                      | Codice produttore                                                                          |
| ManufacturerItemId            | string                                                      | Codice articolo produttore                                                                 |
| VariableItemId                | string                                                      | Codice variante articolo                                                                   |
| VariableId1                   | string                                                      | Tipo variante 1                                                                            |
| VariableId2                   | string                                                      | Tipo variante 2                                                                            |
| VariableValueId1              | string                                                      | Valore variante 1                                                                          |
| VariableValueId2              | string                                                      | Valore variante 2                                                                          |
| ParentLineId                  | string                                                      | Codice alla riga padre                                                                     |
| SourceReference               | string                                                      |                                                                                            |
| CollectOnSite                 | bool                                                        |                                                                                            |
| PackUnitUomId                 | string                                                      | Unità di misura unitaria d'imballo                                                         |
| PackUomId                     | string                                                      | Unità di misura d'imballo                                                                  |
| SalesUomId                    | string                                                      | Unità di misura di vendita                                                                 |
| UnitsPerPack                  | decimal                                                     | Unità per confezione                                                                       |
| PackUnitUomToSalesUomQtyRatio | decimal                                                     | Rapporto di conversione da unità di misura unitaria d'imballo a unità di misura di vendita |
| UnitsPerSalesUom              | decimal                                                     | Unità per unità di misura di vendita                                                       |
| PackUnitQty                   | decimal                                                     | Quantità espressa nell'unità di misura unitaria d'imballo                                  |
| NumberOfPacks                 | decimal                                                     | Numero confezioni                                                                          |
| SalesQty                      | decimal                                                     | Quantità di vendita                                                                        |
| FreeGiftNumberOfPacks         | decimal                                                     | Numero confezioni omaggio                                                                  |
| FreeGiftSalesQty              | decimal                                                     | Quantità di vendita omaggio                                                                |
| SaleTypeId                    | string                                                      | Tipo di vendita                                                                            |
| SaleTypeMode                  | [SaleTypeMode](document-data-model.md#saletypemode)         | Modalità di vendita                                                                        |
| VatRateId                     | string                                                      | Codice IVA                                                                                 |
| VatRateValue                  | decimal                                                     | Valore IVA                                                                                 |
| VatRateIsExemption            | bool                                                        | Esente da IVA                                                                              |
| PriceListId                   | string                                                      | Codice del listino prezzi                                                                  |
| PriceListInfo                 | string                                                      | Informazioni relative al listino prezzi                                                    |
| UnitPrice                     | decimal                                                     | Prezzo unitario articolo                                                                   |
| NetUnitPrice                  | decimal                                                     | Prezzo unitario netto dell'articolo                                                        |
| PricePerQtyMultiplier         | decimal                                                     | Moltiplicatore prezzo quantità                                                             |
| Discounts                     | string                                                      | Sconti                                                                                     |
| TotalDiscount                 | decimal                                                     | Totale sconti                                                                              |
| GrossCost                     | decimal                                                     | Costo lordo                                                                                |
| DiscountOnGrossCost           | decimal                                                     | Sconto su costo lordo                                                                      |
| NetCost                       | decimal                                                     | Costo netto                                                                                |
| Notes                         | string                                                      |                                                                                            |
| DeliveryDate                  | DateTime                                                    | Data consegna                                                                              |
| DeliveryDateTypeId            | string                                                      | Tipo di data consegna                                                                      |
| WarehouseId                   | string                                                      | Codice magazzino                                                                           |
| Amount                        | decimal                                                     | Totale riga                                                                                |
| VatAmount                     | decimal                                                     | Valore IVA                                                                                 |
| AmountIncludingVat            | decimal                                                     | Totale IVA inclusa                                                                         |
| FreeText1..3                  | string                                                      | Campi testuali liberi                                                                      |
| FreeBoolean1..7               | bool                                                        | Campi booleani liberi                                                                      |
| Retail                        | [RetailPrice](./#retailprice)                               | Info prezzo retail                                                                         |
| Original                      | [OriginalInfo](./#originalinfo)                             | Prezzo originale                                                                           |

### RetailPrice

| Campo            | Tipo    | Descrizione             |
| ---------------- | ------- | ----------------------- |
| PriceListId      | string  | Codice listino prezzi   |
| UnitPrice        | decimal | Prezzo unitario         |
| NetUnitPrice     | decimal | Prezzo unitario netto   |
| PriceIncludesVat | bool    | Il prezzo include l'IVA |
| Discounts        | string  | Sconti                  |

### OriginalInfo

| Campo            | Tipo    | Description                       |
| ---------------- | ------- | --------------------------------- |
| PriceListId      | string  | Codice listino prezzi             |
| UnitPrice        | decimal | Prezzo unitario                   |
| NetUnitPrice     | decimal | Prezzo unitario netto             |
| PriceIncludesVat | bool    | Indica se il prezzo include l'IVA |
| Discounts        | string  | Sconti                            |

### Document FamilyId

1. SalesOrders
2. SalesQuotes
3. SalesInvoices
4. NoteCredito
5. DDT
6. Inventories
7. WorkSessions

### UserType

* \-1 Undefined&#x20;
* &#x20;0 Admin&#x20;
* &#x20;1 SalesAgent&#x20;
* &#x20;2 Customer&#x20;
* &#x20;3 Executive

### UserReportMailsUsage

* 0 Default&#x20;
* 1 ShouldSendAsCc&#x20;
* 2 ShouldSendAsBcc

### ItemType

* 0 Normal&#x20;
* 1 Manual&#x20;
* 2 Note&#x20;
* 3 ModelItem&#x20;
* 4 VariableItem&#x20;
* 5 Idrolab&#x20;
* 6 Jolly

### DocumentLineType

* 0: Normal&#x20;
* 1: Manual&#x20;
* 2: Note = 2&#x20;
* 3: ModelItem&#x20;
* 4: VariableItem
* 5: Idrolab&#x20;
* 6: Jolly

### SaleTypeMode

* 0: Normal&#x20;
* 1: TotalFreeSample&#x20;
* 2: TaxableFreeSample&#x20;
* 3: DiscountOnGoo&#x20;
* 4: Promotion

