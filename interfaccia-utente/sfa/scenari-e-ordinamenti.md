# Scenari

Uno Scenario definisce i filtri e gli ordinamenti da applicare ai dati di un Contesto, visualizzati con uno specifico Layout.   
Per ciascuna coppia Contesto\Layout esiste uno Scenario di default non personalizzabile.  
Nel caso in cui vengano definiti Scenari personalizzati, lo Scenario di default non sarà più visibile.

![](../../.gitbook/assets/image%20%2834%29.png)

![](../../.gitbook/assets/image%20%2820%29.png)

**Nota bene:**

Context Id: deve essere specificato uno dei User Case Context definiti in Kimo \(vedi [Elenco](layout/list/)\)

Tipo Ricerca: può essere specificata una delle Rule definite nello User Case Context selezionato \(vedi [Elenco](layout/list/)\).

Layout Id: deve essere specificato uno dei Layout associati al Context Id.

Campi ordinamento: può essere specificato un elenco di campi separati da virgola. Ciascun campo deve rientrare tra i campi definiti per lo User Case Context selezionato \(vedi [Elenco](layout/list/)\).

Priorità ordinamento: è un numero da 0 a N che rappresenta l'ordine di apparizione dello scenario rispetto agli altri. Lo scenario con la priorità 0 è il primo da sinistra.

Filtri addizionali: può essere specificata una condizione di filtro espressa in linguaggio SQL usando agli attributi delle Entity.

### Criteri di Ordinamento

Per ciascun Scenario è possibile definire ulteriori Criteri di ordinamento.  
Ciascun Criterio di ordinamento specifica un elenco di campi dello User Case Context separati da virgola.  
Per ciascun Criterio di ordinamento è possibile specificare la priorità.  
Ogni volta che viene visualizzato uno Scenario che dispone di Criteri di Ordinamento premendo l'apposito tasto è possibile visualizzare la lista dei Criteri di Ordinamento visualizzati in base alla priorità assegnata.



