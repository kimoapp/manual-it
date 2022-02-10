# Cancellare e ripristinare un utente

Un utente può essere cancellato dalla [Console di Amministrazione](../../introduzione/moduli/console-admin.md), impedendogli di continuare ad utilizzare Kimo.

{% hint style="warning" %}
Una volta cancellato l'utente, dalle App che lavorano in modalità offline (es. l'App SFA per iPad) è comunque possibile continuare ad accedere, ma non è possibile eseguire operazioni come la sincronizzazione dei dati. Questo avviene perché l'App lavora appunto in modalità offline, quindi non "recepisce" immediatamente che l'utente è stato cancellato nel server.\
Per limitare il tempo in cui l'App continua a funzionare, consigliamo di impostare i parametri che obbligano gli utenti ad effettuare dalle App una sincronizzazione dei dati entro un certo numero di ore: in questo modo l'utente non potrà continuare ad usare l'App fino a quando non esegue una nuova sincronizzazione, ma tale operazione gli sarà impedita in quanto l'utente è stato cancellato.
{% endhint %}

La cancellazione avviene solo a livello logico, impostando l'utente come "archiviato", ma senza cancellarne effettivamente le informazioni. Questo offre il vantaggio di poter, all'occorrenza, ripristinare l'utente archiviato, rendendolo nuovamente operativo.\
\
Un utente "cancellato" può essere ripristinato premendo il tasto "disarchivia utente" ![](../../.gitbook/assets/disarchivia.PNG) : questo tasto viene visualizzato solo per gli utenti archiviati che normalmente non sono visibili. \
Per rendere visibili questi Utenti utilizzare il filtro di ricerca avanzata "Mostra anche gli utenti archiviati".&#x20;
