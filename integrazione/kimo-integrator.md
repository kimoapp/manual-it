# Kimo integrator

## Impostazioni di sistema <a id="impostazioni-di-sistema"></a>

Attraverso l'entità IntegratorSystemSettings è possibile andare a specificare come far gestire a Kimo Integrator i tipi di dato dell'Erp Integrator.

## Mapping <a id="mapping"></a>

L'entità IntegratorMapping definisce il mapping tra le tabelle di Kimo e le tabelle dell'Erp/Crm. Per definire il mapping tra due tabelle vanno inseriti i seguenti campi:

1. KimoEntity: Il nome dell'entità in Kimo
2. KimoField: Il nome del campo dell'entità in Kimo
3. ErpImportName:Il nome del campo o dell'entità da cui Kimo leggerà i dati
4. ErpExportName: Il nome del campo o dell'entità in cui Kimo scriverà i dati
5. SystemId: Il sistema informativo da cui leggere i dati

## Filtri importazione <a id="filtri-importazione"></a>

L'entità IntegratorImportFilter permette di definire query custom che vengono eseguite nel database di integrazione per poter normalizzare i dati nel formato che richiede Kimo.

