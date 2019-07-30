# Scenari

Uno Scenario definisce i filtri e gli ordinamenti da applicare ai dati di un contesto, visualizzati con uno specifico layout.   
Per ciascuna coppia contesto\layout esiste uno scenario di default non personalizzabile.  
Nel caso in cui vengano definiti scenari personalizzati, lo scenario di default non sarà più visibile.

![](../../.gitbook/assets/image%20%2835%29.png)

![](../../.gitbook/assets/image%20%2820%29.png)

**Nota bene:**

Context Id: deve essere specificato uno dei user case context definiti in Kimo \(vedi [Elenco](layout/list/)\)

Tipo Ricerca: può essere specificata una delle rule definite nello user case context selezionato \(vedi [Elenco](layout/list/)\).

Layout Id: deve essere specificato uno dei layout associati al Context Id.

Campi ordinamento: può essere specificato un elenco di campi separati da virgola. Ciascun campo deve rientrare tra i campi definiti per lo User Case Context selezionato \(vedi [Elenco](layout/list/)\).

Priorità ordinamento: è un numero da 0 a N che rappresenta l'ordine di apparizione dello scenario rispetto agli altri. Lo scenario con la priorità 0 è il primo da sinistra.

Filtri addizionali: può essere specificata una condizione di filtro espressa in linguaggio SQL usando agli attributi delle entità.

### Criteri di Ordinamento

Per ciascun scenario è possibile definire ulteriori criteri di ordinamento.  
Ciascun criterio di ordinamento specifica un elenco di campi dello user case context separati da virgola.  
Per ciascun criterio di ordinamento è possibile specificare la priorità.  
Ogni volta che viene visualizzato uno scenario che dispone di  criteri di ordinamento premendo l'apposito tasto è possibile visualizzare la lista dei criteri di ordinamento visualizzati in base alla priorità assegnata.



