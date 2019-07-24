# Valori di default

Un valore di default definisce il valore da assegnare ad un campo di una entità, quando ne viene eseguita la creazione da parte di un utente. Ad esempio, può essere utilizzato per impostare che quando viene creato un cliente, il campo relativo alla valuta assuma il valore 'EURO' \(corrispondente al codice della valuta\).

A seguire l'elenco delle entità e dei campi che possono essere inizializzati con valori di default.

### Document

| Entità | Campo |
| :--- | :--- |
| Document | TrademarkId |
| Document | SeasonId |
| Document | PaymentMethod |
| Document | IsFatturaPA |
| Document | Mail \(destinatari mail\) |
| Document | FreeBoolean\[1..n\] |
| Document | FreeText\[1..n\] |
| Document | FreeLookup\[1..n\] |
| Document | FreeDecimal\[1..n\] |
| Document | DeliveryDate |
| Document | DeliveryDateTypeId |
| Document | WarehouseId |
| Document | PriceListId |
| Document | RetailPriceListId |
| Document | PaymentMethodId |
| Document | CurrencyId |
| Document | Notes |
| Document | PrivateNotes |
| Document | RegistrationDocumentTypeId |
| Document | ResponsibleForTransportId |
| Document | CarrierId |
| Document | GoodsAspectId |
| Document | ShipmentMethodId |
| Document | TransportModeId |
| Document | TrademarkId |
| Document | SeasonId |
| Document | CupCode |
| Document | CigCode |
| Document | SourceReference |

### DocumentLine

| Entità | Campo |
| :--- | :--- |
| DocumentLine | FreeBoolean\[1..n\] |
| DocumentLine | FreeText\[1..n\] |
| DocumentLine | FreeLookup\[1..n\] |
| DocumentLine | FreeDecimal\[1..n\] |
| DocumentLine | DeliveryDate |
| DocumentLine | DeliveryDateTypeId |
| DocumentLine | WarehouseId |
| DocumentLine | Notes |
| DocumentLine | ItemDescription |
| DocumentLine | SourceReference |
| DocumentLine | SourceReferenceType |
| DocumentLine | FreeTextsCapacity |
| DocumentLine | FreeBooleansCapacity |
| DocumentLine | FreeDecimalsCapacity |
| DocumentLine | FreeLookupsCapacity |

### Account

| Entità | Campo |
| :--- | :--- |
| Account | AccountFilterId |
| Account | Address.Country |
| Account | CustomerDiscountGroupId |
| Account | CurrencyId |
| Account | CustomerGroupId |
| Account | CustomerPriceGroupId |
| Account | CustomerTypeId |
| Account | DeliveryDateTypeId |
| Account | FreeLookups\[1..n\] |
| Account | GoodsAspectId |
| Account | InvoiceDiscountId |
| Account | LanguageId |
| Account | Phone |
| Account | Phone2 |
| Account | MobilePhone |
| Account | PriceListId |
| Account | RetailPriceListId |
| Account | PaymentMethodId |
| Account | RegistrationDocumentTypeId |
| Account | ResponsibleForTransportId |
| Account | ShipmentMethodId |
| Account | StatisticClassId |
| Account | TransportModeId |
| Account | VatRateId |
| Account | WarehouseId |
| Account | ZoneId |

### Activity

| Entità | Campo |
| :--- | :--- |
| Activity | Status |
| Activity | FreeLookup\[1..n\] |

### Contact

| Entità | Campo |
| :--- | :--- |
| Activity | AddressCountry |
| Activity | TitleId |
| Activity | CompanyRoleId |
| Activity | MaritalStatusId |
| Activity | Collapse |

Il valore assunto da ciascun campo può essere personalizzato per utente.

È possibile far sì che, quando si creano certi tipi di entità, alcuni dei valori siano impostati copiando i valori di un'altra entità di partenza: ad esempio, si può far sì che, creando un'offerta o un ordine, degli ulteriori campi \(es. i campi "liberi"\) vengano copiati dal cliente \(oltre ai campi che già normalmente vengono presi dal cliente per inizializzare i documenti di vendita, come il metodo di pagamento o il listino\).   
Un altro tipico caso di utilizzo è relativo alla creazione dei documenti di vendita a partire dai documenti da Erp, utilizzando dei campi di questi ultimi per inizializzare alcuni valori del nuovo documento di vendita \(o delle sue righe\). 

La sintassi per specificare che la sorgente del valore è un campo di una entità è la seguente: 

${&lt;entità&gt;.&lt;campo&gt;} ``

es. ${Account.FreeBoolean1}

Per ciascun entità è possibile specificare solo un sottoinsieme di entità da usare come sorgente.

| Entità | Entità  sorgente |
| :--- | :--- |
| Document | Account |
| DocumentLine | Account |
| DocumentLine | Item |
| DocumentFromErpDocument | ErpDocument |
| DocumentFromErpDocument | Account |
| Cart | Account |

  












