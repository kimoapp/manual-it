# Entity Metadata

In Kimo esistono Entity di vario tipo

* Entity ReadOnly: importate da Erp e mai modificate da Kimo client Es. ErpDocument
* Entity Write: create nativamente da Kimo client Es. Document
* Entity: create da Erp ma modificate da Kimo client Es. Account 
* Entity Server Write: create a a livello di Kimo Consolle, readonly per il client e non esportate verso Erp Es. ErpStatus.

I metadati in particolare sono relativi alle Entity Write infatti definiscono per ciascun campo le regole di editing \(inserimento/modifica\).  
In assenza di Metadati tutti i Campi sono non editabili.

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

 

