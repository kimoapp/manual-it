# Integrator System Settings

Le IntegratorSystemSettings vanno inserite all'interno dell'apposita tabella "IntegratorSystemSetting" presente nel Kimo integrator. Queste impostazioni sono utilizzate in Kimo per due scopi:

* Definire le trasformazioni che devono subire i dati nei passaggi di Export e/o Import
* Definire i provider per entità lette in tempo reale dal gestionale

### Sezioni

In Kimo gestiamo due sorgenti dati: l'Erp e il Crm. Le sezioni delle IntegratorSystemSetting servono a definire per quale sorgente dati è valida l'impostazione; se non specificata la sezione vengono prese solo per l'Erp.\
Le sezioni si definiscono inserendo il SystemId (Crm, Erp) prima della chiave.\
\
Es:\
DataFormat\DateFormat\
Crm\DataFormat\DateFormat\
Erp\DataFormat\DateFormat

### DataFormat

| Chiave                                                       | Descrizione                                                                                                                                                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DateFormat                                                   | Definisce il formato dei campi di tipo Date durante le operazioni di import ed export                                                                                          |
| DateExportFormat                                             | Definisce il formato delle date durante le operazioni di export (Ha maggiore priorità rispetto a DateFormat)                                                                   |
| DateTimeFormat                                               | Definisce il formato dei campi di tipo DateTime durante le operazioni di import ed export                                                                                      |
| DateTimeExportFormat                                         | Definisce il formato dei campi di tipo DateTime durante le operazioni di export (Ha maggiore priorità rispetto a DateTimeFormat)                                               |
| [BooleanFormat](integrator-system-settings.md#booleanformat) | Definisce il formato dei campi di tipo Boolean durante le operazioni di export                                                                                                 |
| DateNullValue                                                | Definisce il valore da inviare durante le operazioni di Export per i campi di tipo Date con valore null                                                                        |
| BooleanNullValue                                             | Definisce il valore da inviare durante le operazioni di Export per i campi di tipo Boolean con valore null                                                                     |
| NumericNullValue                                             | Definisce il valore da inviare durante le operazioni di Export per i campi di tipo Numeric con valore null                                                                     |
| StringNullValue                                              | Definisce il valore da inviare durante le operazioni di Export per i campi di tipo String con valore null                                                                      |
| [StringCase](integrator-system-settings.md#undefined)        | Definisce il case con cui le stringhe devono essere gestite durante le operazioni di Export                                                                                    |
| SingleLineStrings                                            | Fa si che le stringhe vengano scritte tutte su una riga rimuovendo eventuali caratteri che mandano a capo                                                                      |
| IdrolabItemId                                                | Definisce il codice articolo da inviare durante l'Export nel caso di righe documento di tipo Idrolab                                                                           |
| ShipmentSiteIdSplitChar                                      | Definisce il carattere da utilizzare per splittare il codice delle destinazioni merci durante l'Export dei documenti. Viene inviata solo la parte dopo il carattere separatore |
| ItemIdSplitChar                                              | Definisce il carattere da utilizzare per splittare il codice degli articoli durante l'Export dei documenti. Viene inviata solo la parte dopo il carattere separatore           |
| ExportTransformations                                        | Definisce alcune regole custom da applicare durante l'Export dei dati                                                                                                          |

### BooleanFormat

**Valori:**

* ZeroOne

### **StringCase**

**Valori:**

* Invariant
* Upper

### Providers

| Chiave                                                                                      | Descrizione                                                                                                                 |
| ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| [ItemOnlineAvailabilitiesProvider](integrator-system-settings.md#undefined)                 | Definisce il metodo con cui vengono lette le disponibilità online.                                                          |
| [ErpDocumentOnlineProvider](integrator-system-settings.md#undefined)                        | Definisce il metodo con cui vengono letti i documenti da Erp online                                                         |
| [ReassortmentOnlineProvider\\{reassortmentTypeId}](integrator-system-settings.md#undefined) | Definisce il metodo con cui vengono letti i riassortimenti online specificando anche il tipo di riassortimento da ricercare |

### ItemOnlineAvailabilitiesProvider

**Valori:**

* DbView
* DbPolling

### ErpDocumentOnlineProvider

**Valori:**

* DbView

### ReassortmentOnlineProvider

**Valori:**

* DbView

****



.