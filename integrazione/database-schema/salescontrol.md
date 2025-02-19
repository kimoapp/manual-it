---
description: Controlli commerciali sui documenti di vendita
---

# SalesControl

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| ChannelsEnabled | Indica per quali canali è abilitato \(se non specificato vale per tutti i canali\) | enum |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| [MessageVerbosityLevel](salescontrol.md#messageverbositylevel) | Livello di verbosità dei messaggi per le validazioni fallite | enum |  |
| [SalesControlType](salescontrol.md#salescontroltype) | Tipo di controllo | enum |  |
| [SaleTypeTargetContributeTo](salescontrol.md#saletypetargetcontributeto) | Target di Tipi di Vendita che concorrono al controllo commerciale | enum |  |
| [SaleTypeTargetSubjectTo](salescontrol.md#saletypetargetsubjectto) | Target di Tipi di Vendita che sono soggetti al controllo commerciale | enum |  |
| [SeverityLevel](salescontrol.md#severitylevel) | Livello di serietà | enum |  |
| StartDate | Data inizio validità | date |  |
| [Target](salescontrol.md#target) | Target del controllo commerciale | enum |  |
| [UomType](salescontrol.md#uomtype) | Tipo dell'unità di misura \(di vendita o di imballo\) | enum |  |

## MessageVerbosityLevel

* 0: ShowValue
* 1: DoNotShowValue

## SalesControlType

* 1: Prezzo minimo
* 2: Prezzo Unitario non a zero
* 3: Importo minimo
* 4: Sconto massimo
* 5: Sconto medio massimo
* 6: Quantità minima
* 7: Quantità massima
* 8: Vendita per quantità disponibile nel magazzino
* 9: Vendita per quantità disponibile nel centro logistico
* 10: Vendita per quantità disponibile globalmente
* 11: Punti disponibili nel borsellino
* 12: Importo massimo omaggiabile per promozione
* 13: Ripristino condizioni di vendita per quantità non conforme al confezionamento
* 14: Importo minimo \(esclusi documenti con solo merce in omaggio\)
* 15: Quantità non a zero
* 16: Vendita per quantità disponibile nel magazzino viaggiante
* 17: Articolo non più presente nel catalogo
* 18: Vendibilità
* 19: Documento con promozione che non rispetta i vincoli
* 20: Possono essere inviati solo documenti in approvazione
* 21: Non vendibilità
* 22: Articoli obbligatori
* 23: Il documento può contenere solo righe di una singola promozione
* 24: Prezzi del documento aggiornati rispetto a quelli di listino
* 25: Promozione ancora attiva per il documento
* 26: Quantità massima pari a quella presente nella relativa ReassortmentLine
* 27: Importo minimo reso
* 28: Importo minimo documento calcolato con moltiplicatore sull'importo reso
* 29: Le promozioni devono passare per il processo di approvazione
* 30: Cliente bloccato
* 31: Margine minimo percentuale
* 32: Margine minimo in valore
* 33: Importo minimo del documento in presenza di una promozione specifica
* 34: Controllo commerciale generico in cui è possibile specificare un messaggio custom
* 35: Non è possibile confermare ordini su un Prospect

## SaleTypeTargetContributeTo

* 0: Default
* 1: RegularSale
* 2: RegularSale\_WithEditedPriceAndDiscount
* 4: FreeGiftSale\_NotInPromotion
* 8: PromotionSale
* 16: PromotionSale\_NotFreeGift
* 32: PromotionSale\_FreeGift
* 64: Rma

## SaleTypeTargetSubjectTo

* 0: Default
* 1: RegularSale
* 2: RegularSale\_WithEditedPriceAndDiscount
* 4: FreeGiftSale\_NotInPromotion
* 8: PromotionSale
* 16: PromotionSale\_NotFreeGift
* 32: PromotionSale\_FreeGift
* 64: Rma

## SeverityLevel

* 0: Error
* 1: Warning
* 2: ApprovalRequired

## Target

* 1: Document
* 2: DocumentLine
* 3: Item
* 4: Uom
* 5: ItemOrItemVariable
* 6: Encoding

## UomType

* 0: Undefined
* 1: PackUom
* 2: SalesUom
