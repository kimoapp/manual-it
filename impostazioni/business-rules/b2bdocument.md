# B2b\Document

| Valore | Descrizione |
| :--- | :--- |
| [**DocumentNumberForConfirmedCart**](b2bdocument.md#documentnumberforconfirmedcart) | Modalità con cui generare il numero del documento creato in seguito alla conferma di un carrello |
| [**DocumentsFromCartFactory**](b2bdocument.md#documentsfromcartfactory) | Indica il modo in cui devono essere generati i documenti creati in seguito alla conferma di un carrello |
| [**GetDocumentTypeIdForCart**](b2bdocument.md#getdocumenttypeidforcart) |  |
| [**ReportTypeId**](b2bdocument.md#reporttypeid) | Tipo di report da usare \(es. per la generazione del PDF\) |

## DocumentNumberForConfirmedCart

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Usa l'Id del carrello come numero del documento
* 1 =&gt; Genera un numero sequenziale in base al tipo di documento

## DocumentsFromCartFactory

**Tipo:** String  
**Valore di default:** Standard  
**Valori:**

* Febos
* SplitByTrademarkAndSeason
* SplitByWarehouse
* Standard
* Wald

## GetDocumentTypeIdForCart

**Tipo:** String

## ReportTypeId

**Tipo:** String
