# Partite aperte

Le Partite Aperte fanno riferimento all'entità [ReceivableInstallment](../integrazione/database-schema/receivableinstallment.md).\
Le partite aperte rappresentano pagamenti o crediti associati ad un cliente che devono essere ancora saldati.\
Le funzionalità relative alle Partite aperte sono regolate dalle seguenti autorizzazioni a livello di ruolo Agente:

* Può incassare le partite
* Può vedere gli scaduti dei clienti
* Può vedere il registro incassi
* Può vedere le partite dei clienti

### Incassi e Incassi multipli

Accedendo allo scadenzario di un cliente si potranno visualizzare le partite aperte.\
In base alla configurazione del ruolo dell'utente sarà possibile modificare le partite, incassarle e incassarne più di una contemporaneamente.\
Nell'editor proposto per registrare gli incassi,  di default, vengono visualizzate le informazioni relative al pagamento , una casella di editor che permette di inserire l'importo pagato, una data del pagamento e un campo testuale per l'aggiunta di note.\
Nel caso di incassi multipli l'editor indicherà solo in numero di rate su cui si sta lavorando e il residuo.\
Se si effettua un incasso multiplo,inserendo un importo minore del saldo totale, Kimo cercherà di saldare le partite in ordine di importo crescente.

#### Esempio

```
Partita A: importo da pagare 200,00€
Partita B: importo da pagare 230,00€
Partita C: importo da pagare 170,00€

Saldo da pagare: 600,00€
Importo pagato: 450,00€

Verranno saldate le partite C e A e parte della B.
La partita B rimarrà aperta con importo da pagare: 150,00€
```

Data una singola partita è possibile effettuarne più incassi parziali.

### Registro incassi

Nel registro incassi è possibile visualizzare tutti i pagamenti registrati.\
Nel registro vengono visualizzati contemporaneamente le informazioni dei pagamenti registrati indipendentemente dal cliente di riferimento.\
L'unico filtro applicabile è la data, di default sarà utilizzata quella odierna.\
\
