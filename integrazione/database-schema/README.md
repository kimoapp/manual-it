# Database schema

| Entità | Descrizione |
| :--- | :--- |
| [Account](account.md) | Account \(clienti, prospect, destinazioni merci\) |
| [AccountAccountingInfo](accountaccountinginfo.md) | Scheda contabile di un account |
| [AccountBank](accountbank.md) | Banche di un account |
| [AccountFilter](accountfilter.md) | \[OBSOLETO - usare i FreeLookup\] Filtro 'generico' per un cliente |
| [AccountPerPromotionCustomerGroup](accountperpromotioncustomergroup.md) | Associazione Account - PromotionCustomerGroup |
| [Activity](activity.md) | Attività |
| [ActivityAssignee](activityassignee.md) | Utenti a cui è stata assegnata l'attività |
| [ActivityType](activitytype.md) | Tipi di attività |
| [AvailabilityRule](availabilityrule.md) | Regole di disponibilità |
| [AvailabilityRuleParamsPerDocument](availabilityruleparamsperdocument.md) | Criteri per l'applicazione delle regole di disponibilità ai documenti |
| [Bank](bank.md) | Banca |
| [BankAgency](bankagency.md) | Agenzia bancaria |
| [Budget](budget.md) | Budget |
| [BudgetLine](budgetline.md) | Riga di un budget |
| [BudgetLineActual](budgetlineactual.md) | Riga di un budget con i dati "effettivi" registrati dall'Erp |
| [BudgetPerSalesAgent](budgetpersalesagent.md) | Associazione dei Budget agli agenti |
| [BusinessRuleFromErp](businessrulefromerp.md) | Valori per Business Rule definite sull'Erp |
| [Carrier](carrier.md) | Vettore |
| [CatalogPriceList](catalogpricelist.md) | Listini da usare per visualizzare i prezzi nel catalogo |
| [CompanyRole](companyrole.md) | Ruolo aziendale |
| [Contact](contact.md) | Contatti |
| [Country](country.md) | Paese \(nazione\) |
| [Currency](currency.md) | Valuta |
| [CustomerDiscountGroup](customerdiscountgroup.md) | Gruppi sconti clienti |
| [CustomerGroup](customergroup.md) | Gruppi clienti |
| [CustomerPriceGroup](customerpricegroup.md) | Gruppi prezzi clienti |
| [DeliveryDateType](deliverydatetype.md) | Tipi di date di consegna |
| [DiagnosticPriceTestCase](diagnosticpricetestcase.md) | Test diagnostica prezzi |
| [DiscountsPerHierarchy](discountsperhierarchy.md) | Sconti per gerarchia |
| [DiscountsPerItemGroup](discountsperitemgroup.md) | Sconti per gruppo merceologico |
| [DiscountsPerItemSeries](discountsperitemseries.md) | Sconti per serie articolo |
| [Document](document.md) |  |
| [DocumentArchivingReason](documentarchivingreason.md) | Causali di archiviazione dei documenti di vendita \(es. motivi di non acquisto\) |
| [DocumentLine](documentline.md) |  |
| [EntitySyncReferenceForAccount](entitysyncreferenceforaccount.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForActivity](entitysyncreferenceforactivity.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForBudgetLine](entitysyncreferenceforbudgetline.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForContact](entitysyncreferenceforcontact.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForEntityGeoposition](entitysyncreferenceforentitygeoposition.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForMarketingForm](entitysyncreferenceformarketingform.md) | SyncReference delle entità create o modificate in Kimo |
| [EntitySyncReferenceForReceivableInstallment](entitysyncreferenceforreceivableinstallment.md) | SyncReference delle entità create o modificate in Kimo |
| [ErpDocument](erpdocument.md) | Documenti da Erp |
| [ErpDocumentLine](erpdocumentline.md) | Righe dei Documenti da Erp |
| [ErpDocumentPerSalesAgent](erpdocumentpersalesagent.md) | Filtro dei Documenti da Erp per specifici agenti |
| [FreeLookup](freelookup.md) | FreeLookup |
| [FreeLookupTranslation](freelookuptranslation.md) | Traduzioni in lingua dei FreeLookup |
| [GoodsAspect](goodsaspect.md) | Aspetto beni |
| [InvoiceDiscount](invoicediscount.md) | Sconto fattura |
| [InvoiceDiscountParams](invoicediscountparams.md) | Parametri per lo Sconto fattura |
| [Item](item.md) | Articoli |
| [ItemAssociated](itemassociated.md) | Articoli alternativi, sostitutivi o collegati |
| [ItemAttachment](itemattachment.md) | Allegati articoli |
| [ItemCharge](itemcharge.md) | Spese per articoli |
| [ItemChargeType](itemchargetype.md) | Tipi di spese per articoli \(es. RAEE\) |
| [ItemCollection](itemcollection.md) | Collezione articoli |
| [ItemCost](itemcost.md) | Costo articoli \(netto, lordo, ...\) |
| [ItemDiscountGroup](itemdiscountgroup.md) | Gruppi sconti articoli |
| [ItemGender](itemgender.md) | Genere articoli |
| [ItemGroup](itemgroup.md) | Gruppi merceologici |
| [ItemGroupTranslation](itemgrouptranslation.md) | Traduzioni in lingua dei gruppi merceologici |
| [ItemImage](itemimage.md) | Immagini articoli \(percorsi dei file\) |
| [ItemLine](itemline.md) | Linea articolo |
| [ItemListPrice](itemlistprice.md) | Prezzi per articolo |
| [ItemLotOfflineAvailability](itemlotofflineavailability.md) | Disponibilità 'offline' dei lotti |
| [ItemOfflineAvailability](itemofflineavailability.md) | Disponibilità 'offline' degli articoli |
| [ItemSeries](itemseries.md) | Serie articolo |
| [ItemSpecificationField](itemspecificationfield.md) | Specifiche tecniche |
| [ItemSpecificationFieldPerGroup](itemspecificationfieldpergroup.md) | Associazione Classificazioni - Specifiche |
| [ItemSpecificationFieldTranslation](itemspecificationfieldtranslation.md) | Traduzioni in lingua dei campi delle classificazioni |
| [ItemSpecificationFieldValue](itemspecificationfieldvalue.md) | Valori predefiniti per le specifiche tecniche degli articoli |
| [ItemSpecificationGroup](itemspecificationgroup.md) | Classificazioni |
| [ItemSpecificationGroupTranslation](itemspecificationgrouptranslation.md) | Traduzioni in lingua delle classificazioni |
| [ItemSpecificationItemPerGroup](itemspecificationitempergroup.md) | Associazione Classificazioni - Articoli |
| [ItemSpecificationValue](itemspecificationvalue.md) | Valori delle specifiche tecniche degli articoli |
| [ItemTranslation](itemtranslation.md) | Traduzioni in lingua dei FreeLookup |
| [ItemUom](itemuom.md) | Unità di misura degli articoli |
| [ItemUrl](itemurl.md) | Risorse 'online' degli articoli \(schede tecniche online, immagini, ...\) |
| [ItemVariable](itemvariable.md) | Varianti articolo |
| [Language](language.md) | Lingua |
| [LogisticArea](logisticarea.md) | Aree logistiche |
| [LogisticAreaDeliveryDays](logisticareadeliverydays.md) | Giorni di consegna per Area Logistica |
| [Manufacturer](manufacturer.md) | Produttori |
| [ManufacturerImage](manufacturerimage.md) | Immagini produttori \(percorsi dei file\) |
| [ManufacturerTranslation](manufacturertranslation.md) | Traduzioni in lingua dei Produttori |
| [MaritalStatus](maritalstatus.md) | Stato civile |
| [MarketingForm](marketingform.md) | Schede Marketing |
| [MarketingFormFamily](marketingformfamily.md) | Famiglie di schede marketing |
| [MarketingFormField](marketingformfield.md) | Campi delle schede marketing |
| [MarketingFormFieldValue](marketingformfieldvalue.md) | Valori predefiniti per i campi delle schede marketing \(es. per le liste\) |
| [MarketingFormLine](marketingformline.md) | Righe delle Schede Marketing |
| [MarketingFormType](marketingformtype.md) | Tipi di schede marketing |
| [MichelangeloSalesCondition](michelangelosalescondition.md) | Condizioni di vendita nell'Erp Michelangelo |
| [MichelangeloSalesMultiplierCondition](michelangelosalesmultipliercondition.md) | Condizioni di ricarico nell'Erp Michelangelo |
| [NavFashionDocumentDiscounts](navfashiondocumentdiscounts.md) | Sconti sui documenti usati nell'Erp Nav Fashion |
| [NavSalesLineDiscount](navsaleslinediscount.md) | Sconti nell'Erp Nav |
| [NavSalesPrice](navsalesprice.md) | Prezzi di vendita nell'Erp Nav |
| [PaymentMethod](paymentmethod.md) | Modalità di Pagamento \(Termini e Condizioni\) |
| [PaymentType](paymenttype.md) | Tipo di pagamento \(tipo effetto\) |
| [PointsPerSale](pointspersale.md) | Punti per la vendita di articoli |
| [PointsPerSaleBalance](pointspersalebalance.md) | Saldo punti vendita |
| [PriceList](pricelist.md) | Listini prezzi |
| [PricePerQuantityRange](priceperquantityrange.md) | Prezzi per scaglione quantità |
| [Promotion](promotion.md) | Promozioni |
| [PromotionCustomerGroup](promotioncustomergroup.md) | Gruppi promozione clienti |
| [PromotionFilter](promotionfilter.md) | Filtri promozioni |
| [PromotionLine](promotionline.md) | Righe promozioni |
| [Reassortment](reassortment.md) | Riassortimenti |
| [ReassortmentLine](reassortmentline.md) | Righe dei riassortimenti |
| [ReassortmentPerSalesAgent](reassortmentpersalesagent.md) | Filtri dei riassortimenti per agente |
| [ReceivableInstallment](receivableinstallment.md) | Scadenzario |
| [RegistrationDocumentType](registrationdocumenttype.md) | Tipi di documenti di registrazione |
| [ResponsibleForTransport](responsiblefortransport.md) | Cura trasporto |
| [SalesAgent](salesagent.md) | Agenti |
| [SalesAgentPerAccount](salesagentperaccount.md) | Associazione account - agenti |
| [SalesConditionPriority](salesconditionpriority.md) | Priorità delle condizioni di vendita |
| [SalesControl](salescontrol.md) | Controlli commerciali sui documenti di vendita |
| [SalesControlLine](salescontrolline.md) | Righe dei controlli commerciali sui documenti di vendita |
| [SalesDiscountCategory](salesdiscountcategory.md) | Categoria sconto vendita |
| [SaleTypePerItem](saletypeperitem.md) | Tipi di vendita per articolo |
| [Season](season.md) | Stagioni di vendita |
| [SeasonGroup](seasongroup.md) | Gruppi di stagioni di vendita |
| [SeasonPerSeasonGroup](seasonperseasongroup.md) | Associazione stagioni di vendita ai relativi gruppi |
| [ShipmentMethod](shipmentmethod.md) | Porto \(metodo di spedizione\) |
| [ShipmentParamsPerDocument](shipmentparamsperdocument.md) | Parametri per la spedizione di un documento di vendita |
| [ShippingCharge](shippingcharge.md) | Spese di spedizione |
| [SirioItemSalesClassification](sirioitemsalesclassification.md) | Classificazioni di vendita nell'Erp Sirio |
| [SirioSalesCondition](siriosalescondition.md) | Condizioni di vendita nell'Erp Sirio |
| [StatisticClass](statisticclass.md) | Classi statistiche |
| [StatisticReport](statisticreport.md) | Report statistici |
| [Title](title.md) | Titolo di una persona \(es. Dott., Ing., ...\) |
| [Trademark](trademark.md) | Marchi |
| [TrademarkPerAccount](trademarkperaccount.md) | Marchi per cliente |
| [TrademarkPerUser](trademarkperuser.md) | Marchi per agente |
| [TrademarkTranslation](trademarktranslation.md) | Traduzioni in lingua dei marchi |
| [TransportMode](transportmode.md) | Mezzi di trasporto |
| [UomTranslation](uomtranslation.md) | Traduzioni in lingua delle unità di misura |
| [Variable](variable.md) | Varianti |
| [VariableValue](variablevalue.md) | Valori per le varianti |
| [VatRate](vatrate.md) | Aliquote IVA |
| [Warehouse](warehouse.md) | Magazzini |
| [Zone](zone.md) | Zone |
