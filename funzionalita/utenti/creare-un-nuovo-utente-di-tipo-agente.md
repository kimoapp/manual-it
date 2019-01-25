# Creare un nuovo agente

Per creare un nuovo utente di tipo agente, accedere alla console di amministrazione di Kimo \(es. [https://kimo.mycompany.com/admin](https://kimo.mycompany.com/admin)\), selezionare l'area "Utenti", quindi "+ Nuovo utente per agente" e compilare tutti i campi nella maschera che sarà visualizzata:

![](../../.gitbook/assets/nuovo-agente.png)

**Nota bene**: 

1. l'indirizzo mail deve essere univoco, in quanto è utilizzato per la conferma di attivazione dell'utente e può essere usato per funzioni come il reset della password.
2. È possibile creare più utenti per uno stesso agente.

Il campo "Agente" è da selezionare nell'elenco degli agenti abilitati dal sistema informativo e, quindi, attivabili in Kimo: permetterà di collegare l'utente di Kimo con il codice agente del sistema informativo.  
Se l'agente desiderato non è presente in elenco, verificare che tali informazioni siano state importate correttamente dal sistema informativo.

Il campo "ruolo" è da selezionare nell'elenco dei ruoli definiti in Kimo e che abilitano le diverse funzionalità.

Una volta premuto il pulsante "Crea" sarà creato l'utente ed inviata una mail all'indirizzo inserito nel campo "E-mail" contenente il link tramite cui impostare la password ed attivare l'utente: fino a quando l'utente non sarà attivo non sarà possibile fare la sincronizzazione.

Successivamente alla creazione del nuovo utente, accedere alla maschera di dettaglio \(tramite il pulsante![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/22000944744/original/4x9HKCgjY3XGNWMcPqpU72T_RzvTC8lGyw.png?1485475532)presente nella lista degli utenti\) per impostare le ulteriori informazioni \(es. layout, serie numeratore, ...\) come da maschera seguente:

![](../../.gitbook/assets/image%20%283%29.png)

Al termine della creazione dell'utente è necessario effettuare una "Preparazione dati di sync"; per fare ciò selezionare dal menù in alto a destra la voce "Mobile" e poi richiedere la sincronizzazione. Questa procedura può essere di durata variabile in base ai dati presenti nel database \(solitamente compresa tra i 15 e i 30 minuti\).

