# Documenti aziendali e personali

In Kimo è possibile far sì che gli utenti possano visualizzare sul loro dispositivo dei documenti, ad esempio dei file come PDF, Excel, Word, oppure video ed immagini.

Tali documenti possono essere definiti in due modi:

1. come **Documenti Aziendali**: tali file saranno visibili a tutti gli utenti. \
   N.B: è comunque possibile far sì che gli utenti B2B e gli agenti vedano documenti diversi.
2. come **Documenti Personali**: ogni utente vedrà solamente i suoi file. Tale funzione è supportata solo per gli agenti.

I principali formati di file supportati da Kimo sono ".pdf", ".doc" e ".xls", oltre ai principali formati per video ed immagini, ma è possibile che anche altri tipi di file possano essere visualizzati in base alla versione del sistema operativo del dispositivo e di quali applicazioni sono installate in esso.

## Configurazione

1. Nelle "Impostazioni Server" configurare il percorso delle directory da cui prendere i file definendo uno o più dei seguenti valori:
   1. **Per i documenti aziendali per gli agenti**: "CompanyDocuments\SourceDirectory"&#x20;
   2. **Per i documenti aziendali per gli utenti B2B**: "B2bCompanyDocuments\SourceDirectory"&#x20;
   3. **Per i documenti personali per gli agenti**: "UserDocuments\SourceDirectory"&#x20;
      1. All'interno di questa cartella debbono essere presenti delle sotto-cartelle aventi come nome il codice dell'agente, in modo tale che Kimo possa prendere per ogni utente solo i relativi file.
2. Abilitare i permessi che gestiscono questa funzionalità
   1. Per gli agenti, tali permessi si trovano nella sezione "File / Documenti" dei ruoli.
3. Una volta abilitata tale funzionalità, appariranno nel menu principale le funzioni per accedere ai documenti aziendali e personali.\
.