# Disponibilità Online

### Setup funzionalità

#### Autorizzazioni

Per il ruolo interessato abilitare l'autorizzazione "Può vedere le disponibilità online della sezione Articoli". Quest'autorizzazione abiliterà la visualizzazione del pulsante per il download della disponibilità online all'interno del documento.

#### Integrazione

Nelle impostazioni dell'integrazione specificare il provider con cui reperire le disponibilità online Key(Providers\ItemOnlineAvailabilitiesProvider): i tipi di provider supportati sono DbView e DbPolling.

* DbView: La tabella delle disponibilità viene letta secondo le logiche standard di integrazione prendendo in considerazione il mapping di ItemOnlineAvailability. \
  Nell'IntegratorMapping devono necessariamente essere specificati i campi da aggiornare. \
  Se è presente un IntegratorImportFilter per la suddetta tabella, la CustomQuery dovrà necessariamente restituire campi con nomi diversi da quelli presenti in Kimo.
* DbPolling: Kimo scrive nella tabella delle disponibilità del database di integrazione i codici articolo per cui vorrebbe ricevere la disponibilità aggiornata e rimane in attesa che il gestionale scriva in quella tabella i valori aggiornati. La tabella su cui va a scrivere Kimo è quella mappata in import per ItemOnlineAvailability. \
  Anche in questo caso, se presente, la CustomQuery dell'IntegratorImportFilter non deve restituire il nome del campo in Kimo e nell'IntegratorMapping devono necessariamente essere presenti i mapping necessari per i campi che si vogliono aggiornare.
