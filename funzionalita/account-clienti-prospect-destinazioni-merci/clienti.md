# Clienti

Il Cliente è il soggetto a cui viene intestato il Documento di vendita creato con Kimo.\
\
Le informazione del Cliente, su Kimo SFA, sono gestite negli appositi [Layout Kimo](../../interfaccia-utente/sfa/layout/list/#account-clienti-prospect-destinazioni-merci).

Il Cliente è un'entità principalmente creata a livello Erp e successivamente inviata a Kimo in fase di Import.\
Il Cliente è un'entità che può essere creata e\o modificata in Kimo se il Ruolo ha l'autorizzazione a farlo (vedi [Ruolo Agente](../../impostazioni/ruoli.md#definizione-di-un-ruolo-per-agenti)).

Il Cliente può essere visualizzato nei vari moduli Kimo SFA , la creazione di un cliente può essere effettuata solo nei moduli SFA App e Web.\
Un Cliente può essere modificato solo nel modulo SFA App.

In fase di Export verso l'Erp i dati dei Clienti creati e/o modificati in Kimo vengono inviati all' Erp.\
L' Erp effettua una validazione dei Clienti e le relative modifiche provenienti da Kimo e ne determina l'esito.\
Alla successiva Importazione l' Erp restituisce l'esito della verifica.\
La logica d'integrazione applicata da Kimo prevede che in caso di esito positivo, all'identificativo del Cliente Kimo venga associato un codice Cliente Erp.

In Kimo le principali funzionalità legate ai Clienti sono le seguenti:

* [Documenti di vendita](../documenti-di-vendita/)
* Riassortimenti
* Documenti da Erp
* [Statistiche](../statistiche.md)
* Credito&#x20;
* Attività

Ulteriori funzionalità sono attivabili tramite le seguenti autorizzazioni presenti nel Ruolo di tipo Agente:

1. "Può creare nuovi clienti"
2. "Può modificare i clienti"
3. "Può scaricare l'estratto conto per i clienti"
4. "Può visualizzare gli sconti delle condizioni di vendita"

.