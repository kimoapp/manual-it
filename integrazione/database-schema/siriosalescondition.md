---
description: Condizioni di vendita nell'Erp Sirio
---

# SirioSalesCondition

**Chiavi**

* _Id_
* SourceType, CampaignFlag, CampaignType, AccountId, CustomerCategory1, CustomerCategory2, ItemId, Lot, ItemSalesClassificationCategoryId, ItemSalesClassification1, ItemSalesClassification2, ItemSalesClassification3, ItemSalesClassification4, ItemSalesClassification5, ItemSalesClassification6, ItemSalesClassification7, ItemSalesClassification8, ItemSalesClassification9, ItemSalesClassification10, PriceListId, ItemLineId, ItemSeriesId, CatalogId, CurrencyId, StartDate, EndDate

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| AccountId | Id del cliente | text | 50 |
| AdditionalOrSubstitutiveDiscountFlag | Flag sconto aggiuntivo o sostitutivo | text | 20 |
| ApplyDiscountFlag | Flag applica sconto prezzo listino | text | 20 |
| ApplyDiscountForQuantityRangeFlag | Flag applicazione sconto quantità | text | 20 |
| CampaignFlag | Flag campagna | text | 20 |
| CampaignType | Tipo campagna | text | 20 |
| CatalogId | Id del catalogo | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerCategory1 | Categoria Merceologica Cliente 1 | text | 50 |
| CustomerCategory2 | Categoria Merceologica Cliente 2 | text | 50 |
| Discount1 | Sconto | dec |  |
| Discount2 | Sconto | dec |  |
| Discount3 | Sconto | dec |  |
| Discount4 | Sconto | dec |  |
| EndDate | Data fine validità | date |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| ItemLineId | Id della linea articolo | text | 50 |
| ItemSalesClassification1 | Classificazione per listini | text | 50 |
| ItemSalesClassification10 | Classificazione per listini | text | 50 |
| ItemSalesClassification2 | Classificazione per listini | text | 50 |
| ItemSalesClassification3 | Classificazione per listini | text | 50 |
| ItemSalesClassification4 | Classificazione per listini | text | 50 |
| ItemSalesClassification5 | Classificazione per listini | text | 50 |
| ItemSalesClassification6 | Classificazione per listini | text | 50 |
| ItemSalesClassification7 | Classificazione per listini | text | 50 |
| ItemSalesClassification8 | Classificazione per listini | text | 50 |
| ItemSalesClassification9 | Classificazione per listini | text | 50 |
| ItemSalesClassificationCategoryId | Id categoria classificazione listini | text | 50 |
| ItemSeriesId | Id della fascia | text | 50 |
| Lot | Lotto | text | 50 |
| Markup1 | Ricariche | dec |  |
| Markup2 | Ricariche | dec |  |
| NetPriceFlag | Flag prezzo netto listino | text | 20 |
| NetPriceForQuantityRangeFlag | Flag prezzi netti per quantità | text | 20 |
| PriceListId | Id del listino | text | 50 |
| PriceListInfo | Info listino | text | text |
| QuantityRange1\_Discount | Sconto per scaglione qta | dec |  |
| QuantityRange1\_Quantity | Quantità per scaglione | dec |  |
| QuantityRange1\_UnitPrice | Prezzo unitario per scaglione qta | dec |  |
| QuantityRange2\_Discount | Sconto per scaglione qta | dec |  |
| QuantityRange2\_Quantity | Quantità per scaglione | dec |  |
| QuantityRange2\_UnitPrice | Prezzo unitario per scaglione qta | dec |  |
| QuantityRange3\_Discount | Sconto per scaglione qta | dec |  |
| QuantityRange3\_Quantity | Quantità per scaglione | dec |  |
| QuantityRange3\_UnitPrice | Prezzo unitario per scaglione qta | dec |  |
| QuantityRange4\_Discount | Sconto per scaglione qta | dec |  |
| QuantityRange4\_Quantity | Quantità per scaglione | dec |  |
| QuantityRange4\_UnitPrice | Prezzo unitario per scaglione qta | dec |  |
| RetrievePriceFlag | Flag reperimento prezzo listino | text | 20 |
| RetrieveQuantityDiscountFlag | Flag reperimento prezzo listino | text | 20 |
| SourceType | Sorgente dei dati \(tabella di origine in Sirio\) | text | 50 |
| StartDate | Data inizio validità | date |  |
| UnitPrice | Prezzo unitario | dec |  |
| UnitPriceIncludingVat | Prezzo unitario ivato | dec |  |
