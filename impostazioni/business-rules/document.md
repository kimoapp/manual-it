# Document

| Valore | Descrizione |
| :--- | :--- |
| [**CanSkipSalesControlsValidationsUsingUnlockCode**](document.md#canskipsalescontrolsvalidationsusingunlockcode) |  |
| [**CigCodeMandatoryIfIsFatturaPA**](document.md#cigcodemandatoryifisfatturapa) | Il Codice Identificativo Gara è obbligatorio se il tipo di documento è FatturaPA |
| [**CollectOnSiteIsMandatoryToChangeWarehouse**](document.md#collectonsiteismandatorytochangewarehouse) | Può essere modificato il magazzino solo se si utilizza il ritiro al banco |
| [**CupCodeMandatoryIfIsFatturaPA**](document.md#cupcodemandatoryifisfatturapa) | Il Codice Unico di Progetto è obbligatorio se il tipo di documento è FatturaPA |
| [**DatesPolicy**](document.md#datespolicy) | Policy di inizializzazione e gestione delle date del documento |
| [**DaysToAddToDocumentDateForDeliveryDate**](document.md#daystoaddtodocumentdatefordeliverydate) | Giorni da aggiungere alla data del documento per calcolare la data di consegna |
| [**DefaultSeason**](document.md#defaultseason) | Stagione di default con cui inizializzare il documento |
| [**DocumentNumberGlobalTemplate**](document.md#documentnumberglobaltemplate) | Template da utilizzare per generare i numeri dei documenti |
| [**DocumentTypesThatRequireApprovalByAccount**](document.md#documenttypesthatrequireapprovalbyaccount) | Tipi di documenti che richiedono l'approvazione da parte del cliente |
| [**ExpectedClosingDatePostponeDays**](document.md#expectedclosingdatepostponedays) | Numero di giorni proposti durante la posticipazione dei documenti, rispetto alla data di scadenza |
| [**HighlightShipmentSiteExistence**](document.md#highlightshipmentsiteexistence) | Indica se il controllo per la selezione delle destinazioni merci deve mettere in evidenza l'esistenza di destinazioni merci |
| [**InfoToShowOnOpen**](document.md#infotoshowonopen) | Informazioni da mostrare all'apertura dell'editor del documento |
| [**MaxDaysWithExpiredDocuments**](document.md#maxdayswithexpireddocuments) | Numero massimo di giorni per cui possono essere consentiti documenti scaduti |
| [**PricesReferenceDateUpdateMode**](document.md#pricesreferencedateupdatemode) | Modalità di aggiornamento della data di riferimento per il calcolo dei prezzi |
| [**QuantitiesSummaryTemplate**](document.md#quantitiessummarytemplate) |  |
| [**ReportSignatureRequireMode**](document.md#reportsignaturerequiremode) | Modalità di avviso per report non firmato |
| [**ShipmentSiteIsMandatoryIfCustomerHasAtLeastOne**](document.md#shipmentsiteismandatoryifcustomerhasatleastone) | La destinazioni merci deve essere selezionata se il cliente ne ha almeno una |
| [**ShouldApplyShipmentParamsOnDocumentLine**](document.md#shouldapplyshipmentparamsondocumentline) | Indica se i parametri di spedizione devono essere applicati alle linee del documento |
| [**ShouldAskArchivingReason**](document.md#shouldaskarchivingreason) | Indica se deve essere richiesta la causale di archiviazione |
| [**ShouldIgnoreAvailabilitySalesControlsAccordingToLoseRemaining**](document.md#shouldignoreavailabilitysalescontrolsaccordingtoloseremaining) | Ignora i controlli commerciali sulle disponibilità in assenza della perdita residuo |
| [**ShouldUpdateAvailabilitiesBeforeDocumentCheckout**](document.md#shouldupdateavailabilitiesbeforedocumentcheckout) | Aggiorna le disponibilità della merce prima di effettuare il checkout |
| [**ShouldUpdateDeliveryDateAccordingToFulfillmentDate**](document.md#shouldupdatedeliverydateaccordingtofulfillmentdate) | Ricalcola la data di consegna in base alla data di evadibilità della merce |
| [**TakeShipmentSiteAsDefaultIfHasOnlyOne**](document.md#takeshipmentsiteasdefaultifhasonlyone) | Se è presente una sola destinazione merci per un cliente, viene selezionata di default all'interno dei documenti |
| [**TotalAmountDiscountsPriority**](document.md#totalamountdiscountspriority) | Definisce la priorità con cui vengono applicati gli sconti nel totale documento |
| [**ValuesToTakeFromShipmentSite**](document.md#valuestotakefromshipmentsite) | Template per la descrizione delle attività create dai Documenti da Erp |
| [**VisibleDiscounts**](document.md#visiblediscounts) | Indica gli sconti da visualizzare all'interno dell'editor documento |
| [**VisibleLineDiscounts**](document.md#visiblelinediscounts) | Indica gli sconti da visualizzare all'interno dell'editor delle linee di un documento |
| [**VisiblePaymentDiscounts**](document.md#visiblepaymentdiscounts) | Indica gli sconti associati al metodo di pagamento da visualizzare all'interno dell'editor documento |
| [**WarningDaysWithExpiredDocuments**](document.md#warningdayswithexpireddocuments) | Numero di giorni dopo la scadenza del documento in cui dare un messaggio di warning |

## CanSkipSalesControlsValidationsUsingUnlockCode

**Tipo:** Boolean

## CigCodeMandatoryIfIsFatturaPA

**Tipo:** Boolean

## CollectOnSiteIsMandatoryToChangeWarehouse

**Tipo:** Boolean

## CupCodeMandatoryIfIsFatturaPA

**Tipo:** Boolean

## DatesPolicy

**Tipo:** String  
**Valore di default:** Standard

## DaysToAddToDocumentDateForDeliveryDate

**Tipo:** Int32

## DefaultSeason

**Tipo:** String

## DocumentNumberGlobalTemplate

**Tipo:** String

## DocumentTypesThatRequireApprovalByAccount

**Tipo:** Valori separati da pipe

## ExpectedClosingDatePostponeDays

**Tipo:** Valori separati da pipe  
**Valore di default:** 1\|5\|10

## HighlightShipmentSiteExistence

**Tipo:** Boolean

## InfoToShowOnOpen

**Tipo:** String

## MaxDaysWithExpiredDocuments

**Tipo:** Nullable`1

## PricesReferenceDateUpdateMode

**Tipo:** Enum  
**Valori:**

* 0 =&gt; DoNotChange
* 1 =&gt; KeepUpdatedToToday

## QuantitiesSummaryTemplate

**Tipo:** String

## ReportSignatureRequireMode

**Tipo:** Enum  
**Valori:**

* 0 =&gt; No
* 1 =&gt; Warning

## ShipmentSiteIsMandatoryIfCustomerHasAtLeastOne

**Tipo:** Boolean

## ShouldApplyShipmentParamsOnDocumentLine

**Tipo:** Boolean

## ShouldAskArchivingReason

**Tipo:** Boolean

## ShouldIgnoreAvailabilitySalesControlsAccordingToLoseRemaining

**Tipo:** Enum  
**Valori:**

* 0 =&gt; No
* 1 =&gt; WhenLoseRemainingIsFalse
* 2 =&gt; WhenLoseRemainingIsTrue

## ShouldUpdateAvailabilitiesBeforeDocumentCheckout

**Tipo:** Boolean

## ShouldUpdateDeliveryDateAccordingToFulfillmentDate

**Tipo:** Boolean

## TakeShipmentSiteAsDefaultIfHasOnlyOne

**Tipo:** Boolean

## TotalAmountDiscountsPriority

**Tipo:** Valori separati da pipe  
**Valori:**

* 1 =&gt; DocumentDiscounts
* 2 =&gt; DocumentPaymentDiscounts

## ValuesToTakeFromShipmentSite

**Tipo:** Valori separati da pipe  
**Valori:**

* CustomerDiscountGroup
* CustomerGroup
* CustomerPriceGroup
* Discounts
* PaymentMethod
* PriceList
* RetailPriceList
* VatRate

## VisibleDiscounts

**Tipo:** Valori separati da pipe

## VisibleLineDiscounts

**Tipo:** Valori separati da pipe

## VisiblePaymentDiscounts

**Tipo:** Valori separati da pipe

## WarningDaysWithExpiredDocuments

**Tipo:** Nullable`1
.