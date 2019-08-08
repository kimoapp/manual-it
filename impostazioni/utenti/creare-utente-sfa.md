---
description: Utente di tipo Agente
---

# Creare un utente per SFA

Per creare un nuovo utente di tipo Agente, accedere alla [Console di Amministrazione](../../introduzione/moduli/console-admin.md), selezionare l'area "Utenti", quindi "Nuovo utente per agente" e compilare tutti i campi nella maschera che viene visualizzata:

![](../../.gitbook/assets/nuovo-agente.png)

**Nota bene**: 

1. l'indirizzo mail deve essere univoco, in quanto è utilizzato per la conferma di attivazione dell'utente e può essere usato per funzioni come il reset della password.
2. È possibile creare più utenti per uno stesso agente.

Il campo "Agente" è da selezionare nell'elenco degli agenti abilitati dall'Erp e, quindi, attivabili in Kimo: permette di collegare l'utente di Kimo con il codice agente del Sistema Informativo.  
Se l'agente desiderato non è presente in elenco, verificare che tali informazioni siano state importate correttamente dal sistema informativo.

Il campo "Ruolo" è da selezionare nell'elenco dei ruoli definiti in Kimo, necessari per abilitare le diverse funzionalità per l'utente \(vedi la sezione [Ruoli ](../ruoli.md)per la loro definizione\).

Una volta premuto il pulsante "Crea" viene creato l'utente ed inviata una mail all'indirizzo inserito nel campo "E-mail" contenente il link tramite cui impostare la password ed attivare l'utente.  
Fino a quando l'utente non è attivo non è possibile effettuare alcuna operazione.

Finché l'utente non viene attivato, nella lista utenti sono visibili i seguenti pulsanti ![](../../.gitbook/assets/image%20%2821%29.png) e ![](../../.gitbook/assets/image%20%2814%29.png) che  
permettono di inviare nuovamente la mail di attivazione oppure di accedere direttamente al link di attivazione \([Attivare un utente](attivazione-di-un-utente.md)\).

L'utente può essere "cancellato" premendo il tasto ![](../../.gitbook/assets/delete.PNG) \([Cancellare e ripristinare un utente](archiviazione-e-ripristino.md)\).

Successivamente alla creazione del nuovo utente, accedere alla maschera di dettaglio \(tramite il pulsante![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/22000944744/original/4x9HKCgjY3XGNWMcPqpU72T_RzvTC8lGyw.png?1485475532)presente nella lista degli utenti\) per impostare le ulteriori informazioni \(es.configurazione per i layout, serie numeratore, ...\) come da maschera seguente:

![](../../.gitbook/assets/image%20%2820%29.png)

{% hint style="warning" %}
Al termine della creazione dell'utente è necessario effettuare una "Preparazione dati di sincronizzazione", altrimenti non sarà possibile sincronizzarne i dati dall'App. Per fare ciò selezionare dal menù in alto a destra la voce "Import" e successivamente eseguire lo step relativo alla "Preparazione dati di sincronizzazione". Questa procedura può essere di durata variabile in base ai dati presenti nel database \(solitamente compresa tra i 15 e i 30 minuti\).  
In alcune situazioni potrebbe essere necessario anche importare i dati dall'Erp, se quest'ultimo non metteva finora a disposizione di Kimo i dati collegati al nuovo agente \(es. i relativi clienti\).
{% endhint %}

