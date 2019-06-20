# Metadati sulle entità

In Kimo esistono entità di vario tipo:

* Entità in "sola lettura": importate dal Sistema Informativo \(Erp, Crm, ...\) e mai modificate in Kimo \(es. Documenti da Erp, anagrafica dei metodi di pagamento, condizioni di vendita, ...\).
* Entità creabili e/o modificabili nelle App di Kimo \(es. clienti, documenti di vendita, incassi, ...\).
* Entità di supporto creabili dalla [Console di Amministrazione](../introduzione/moduli/console-admin.md) di Kimo \(es. i tipi di documenti di vendita, i tipi di attività, i tipi di riassortimento, FreeLookup, ...\). Sono entità che gli utenti delle App di Kimo vedono in "sola lettura", non possono apportare modifiche ad esse, e non vengono esportate ai Sistemi Informativi.

I metadati in particolare si riferiscono alle entità creabili/modificabili dagli utenti attraverso le App di Kimo: definiscono per ciascun campo delle entità le regole di editing, come ad esempio la lunghezza massima per i campi di testo, l'obbligatorietà dell'inserimento di un determinato campo e così via.  
  
Se non vengono definiti i metadati per un'entità, i suoi campi risulteranno in sola lettura nelle App di Kimo.

### Metadati a livello di entity

Indicano i criteri di applicazione dei Metadati a livello di Campi.

| Chiave | Descrizione |
| :--- | :--- |
| Contesto | Vincolo rispetto al valore del campo &lt;Entity&gt;TypeId nella forma \["&lt;valore1&gt;", "&lt;valoreN&gt;"\] |
| Origine | Vincolo rispetto all'origine del dato: Erp, CreatedOnKimo, EditedOnKimo |
| Padre | Indica che l'entity eredita i metadati dall' entity specificata e li estende. |
| Utenti | Indica per quali Utenti applicare i metadati Es. \["User\_6", "User\_10",...\] |
| Agenti | Indica per quali Agenti applicare i metadati Es. \["01", "02",...\] |
| Ruoli | Indica per quali Ruoli applicare i metadati Es. \["Role\_03", "Role\_02",...\] |

### Metadati a livello di campo

Un Metadato a livello di Campo indica la regola di editing da applicare al valore assegnato al campo.   
Ad un Campo possono essere applicate una o più regole di editing.

| Attributo | Descrizione | Tipo |
| :--- | :--- | :--- |
| Editabile | Indica se il campo può essere modificato | bool |
| Lunghezza Massima | Applicabile solo per i campi di tipo string. Indica la lunghezza massima che può assumere il valore. | int |
| Resettabile | Indica se deve essere visibile il tasto "Reset" del dato. | bool |
| Nullable | Indica se il campo può essere impostato a NULL | bool |
| Obbligatorietà | Indica se la valorizzazione del campo è obbligatoria | bool |
| Pattern Regex | Indica un'espressione regolare verificata in fase di salvataggio dell'Entity. La sintassi da usare è quella del linguaggio C\#. | string |

 

