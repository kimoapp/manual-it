# DocumentLine

| Valore | Descrizione |
| :--- | :--- |
| [**DefaultNumberOfPacks**](documentline.md#defaultnumberofpacks) |  |
| [**DefaultSalesQty**](documentline.md#defaultsalesqty) |  |
| [**FreeGiftSaleTypeId**](documentline.md#freegiftsaletypeid) | Indica il Tipo Vendita da impostare per la riga omaggio |
| [**IsEnabledInlineFreeGift**](documentline.md#isenabledinlinefreegift) | Abilita la possibilita di inserire quantità omaggio nella stessa linea documento contenente la quantità a pagamento |
| [**RecalculatePriceOnUomChange**](documentline.md#recalculatepriceonuomchange) |  |
| [**ReferenceQtyOnUomChange**](documentline.md#referenceqtyonuomchange) |  |
| [**ShouldInitUnitPriceFromIdrolab**](documentline.md#shouldinitunitpricefromidrolab) | Indica se il prezzo va inizializzato da Idrolab |
| [**ShouldLockDiscountsOnUnitPriceEditing**](documentline.md#shouldlockdiscountsonunitpriceediting) | Indica se bloccare gli sconti quando viene modificato il prezzo unitario |
| [**ShouldResetDiscountsOnUnitPriceEditing**](documentline.md#shouldresetdiscountsonunitpriceediting) | Indica se azzerare gli sconti quando viene modificato il prezzo unitario |
| [**UnitsPerPackDivisibilityRule\_Field**](documentline.md#unitsperpackdivisibilityrule_field) |  |
| [**ViewMode**](documentline.md#viewmode) | Modalità di visualizzaione delle linee di un documento |
| [**VisibleDiscounts**](documentline.md#visiblediscounts) | Sconti visualizzati all'interno dell'editor |

## DefaultNumberOfPacks

**Tipo:** Decimal

## DefaultSalesQty

**Tipo:** Decimal

## FreeGiftSaleTypeId

**Tipo:** String

## IsEnabledInlineFreeGift

**Tipo:** Boolean

## RecalculatePriceOnUomChange

**Tipo:** Boolean

## ReferenceQtyOnUomChange

**Tipo:** Enum  
**Valori:**

* 0 =&gt; NumberOfPacks
* 1 =&gt; SalesQty

## ShouldInitUnitPriceFromIdrolab

**Tipo:** Boolean

## ShouldLockDiscountsOnUnitPriceEditing

**Tipo:** Boolean

## ShouldResetDiscountsOnUnitPriceEditing

**Tipo:** Boolean

## UnitsPerPackDivisibilityRule\_Field

**Tipo:** Enum  
**Valori:**

* 0 =&gt; SalesQty
* 1 =&gt; PackUnitQty

## ViewMode

**Tipo:** Enum  
**Valori:**

* 0 =&gt; GroupedByModelItem
* 1 =&gt; GroupedByVariable1

## VisibleDiscounts

**Tipo:** Valori separati da pipe  
**Valore di default:** 1\|2\|3\|4\|5

