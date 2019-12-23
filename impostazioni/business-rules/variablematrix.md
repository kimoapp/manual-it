# VariableMatrix

| Valore | Descrizione |
| :--- | :--- |
| [**BackgroundStyle**](variablematrix.md#backgroundstyle) | Stile del background |
| [**CellDescriptionTemplate**](variablematrix.md#celldescriptiontemplate) | Info visualizzate nel footer della matrice |
| [**CellDescriptionTemplateForDocument**](variablematrix.md#celldescriptiontemplatefordocument) | Info visualizzate nel footer della matrice nel contesto del documento |
| [**ColumnHeaderCellHeight**](variablematrix.md#columnheadercellheight) | Altezza dell'intestazione delle colonne |
| [**DescriptionFontSize**](variablematrix.md#descriptionfontsize) | Dimensione del carattere della descrizione della variante selezionata |
| [**Document\_ColumnHeaderTemplate**](variablematrix.md#document_columnheadertemplate) | Template del testo visualizzato nell'intestazione delle colonne |
| [**Document\_RowHeaderTemplate**](variablematrix.md#document_rowheadertemplate) | Template del testo visualizzato nell'intestazione delle righe |
| [**EnableVirtualAvailability**](variablematrix.md#enablevirtualavailability) | Abilita la disponibilità virtuale |
| [**IndicatorHeight**](variablematrix.md#indicatorheight) | Altezza degli indicatori situati nella casella delle quantità \(es. per mostrare la disponibilità\) |
| [**IndicatorWidth**](variablematrix.md#indicatorwidth) | Larghezza degli indicatori situati nella casella delle quantità \(es. per mostrare la disponibilità\) |
| [**InfoPaneHeight**](variablematrix.md#infopaneheight) | Altezza del pannello informativo |
| [**RowHeaderCellWidth**](variablematrix.md#rowheadercellwidth) | Larghezza dell'intestazione delle colonne |
| [**ValueCellHeight**](variablematrix.md#valuecellheight) | Altezza dalle caselle contenenti la quantità |
| [**ValueCellWidth**](variablematrix.md#valuecellwidth) | Larghezza dalle caselle contenenti la quantità |
| [**ZoneRightBottomValueType**](variablematrix.md#zonerightbottomvaluetype) | Tipo di dato visualizzato in basso a destra nella casella delle quantità \(es. per mostrare la disponibilità\) |
| [**ZoneRightTopValueType**](variablematrix.md#zonerighttopvaluetype) | Tipo di dato visualizzato in alto a destra nella casella delle quantità \(es. per mostrare la disponibilità\) |

## BackgroundStyle

**Tipo:** Enum  
**Valore di default:** 2  
**Valori:**

* 1 =&gt; Flat
* 2 =&gt; Alternate

## CellDescriptionTemplate

**Tipo:** String  
**Valore di default:** ${VariableValue1.Description}, ${VariableValue2.Description}

## CellDescriptionTemplateForDocument

**Tipo:** String  
**Valore di default:** ${VariableValue1.Description}, ${VariableValue2.Description}

## ColumnHeaderCellHeight

**Tipo:** Int32

## DescriptionFontSize

**Tipo:** Decimal

## Document\_ColumnHeaderTemplate

**Tipo:** String

## Document\_RowHeaderTemplate

**Tipo:** String

## EnableVirtualAvailability

**Tipo:** Boolean

## IndicatorHeight

**Tipo:** Int32

## IndicatorWidth

**Tipo:** Int32

## InfoPaneHeight

**Tipo:** Int32

## RowHeaderCellWidth

**Tipo:** Int32

## ValueCellHeight

**Tipo:** Int32

## ValueCellWidth

**Tipo:** Int32

## ZoneRightBottomValueType

**Tipo:** Enum  
**Valori:**

* 0 =&gt; None
* 1 =&gt; Availability\_Warehouse
* 2 =&gt; Availability\_Global
* 3 =&gt; Availability\_Calculated
* 4 =&gt; Availability\_ErpStatus1
* 5 =&gt; Availability\_ErpStatus2
* 6 =&gt; Availability\_ErpStatus3
* 7 =&gt; ItemVariable\_FreeText1
* 8 =&gt; ItemVariable\_FreeText2

## ZoneRightTopValueType

**Tipo:** Enum  
**Valori:**

* 0 =&gt; None
* 1 =&gt; Availability\_Warehouse
* 2 =&gt; Availability\_Global
* 3 =&gt; Availability\_Calculated
* 4 =&gt; Availability\_ErpStatus1
* 5 =&gt; Availability\_ErpStatus2
* 6 =&gt; Availability\_ErpStatus3
* 7 =&gt; ItemVariable\_FreeText1
* 8 =&gt; ItemVariable\_FreeText2
