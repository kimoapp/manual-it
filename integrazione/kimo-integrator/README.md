# Kimo integrator

## Impostazioni di sistema <a id="impostazioni-di-sistema"></a>

Attraverso l'entità IntegratorSystemSettings è possibile andare a specificare come far gestire a Kimo Integrator i tipi di dato dell'Erp Integrator.

## Mapping <a id="mapping"></a>

L'entità IntegratorMapping definisce il mapping tra le tabelle di Kimo e le tabelle dell'Erp/Crm. Per definire il mapping tra due tabelle è necessario specificare i seguenti valori:

1. KimoEntity: nome dell'entità in Kimo
2. KimoField: nome del campo dell'entità in Kimo
3. ErpImportName: nome del campo o dell'entità \(tabella, vista\) da cui Kimo leggerà i dati
4. ErpExportName: nome del campo o dell'entità in cui Kimo scriverà i dati
5. SystemId: sistema informativo da cui leggere i dati

Es. Mappatura in Import della tabella CustomerGroup

| KimoEntity | KimoField | ErpImportName | ErpExportName | SystemId |
| :--- | :--- | :--- | :--- | :--- |
| CustomerGroup |  | ErpCustomerGroup | NULL | NULL |
| CustomerGroup | Id | CODE | NULL | NULL |
| CustomerGroup | Description | DESCRIPTION | NULL | NULL |

{% hint style="info" %}
Nel caso in cui i nomi dei campi dell'entità Erp corrispondano ai nomi dei campi della corrispondente tabella Kimo, per effettuare la mappatura sarà sufficiente creare un solo record con la mappatura della tabella e non sarà necessario specificare la mappatura di tutti i campi.  
{% endhint %}

## Filtri importazione <a id="filtri-importazione"></a>

L'entità IntegratorImportFilter permette di definire query custom che vengono eseguite nel database di integrazione per poter normalizzare i dati nel formato richiesto da Kimo.  
Per definire un filtro è necessario specificare i seguenti valori:

1. KimoEntity: nome dell'entità in Kimo
2. AdditionalFilter: Clausula where da aggiungere alla query eseguita
3. CustomQuery: select sql effettuata sul database d'integrazione Erp. La tabella risultante può essere mappata in Import verso Kimo. Se la struttura della tabella risultante replica la struttura della tabella Kimo la mappatura non è necessaria.
4. SystemId: sistema informativo da cui leggere i dati 



