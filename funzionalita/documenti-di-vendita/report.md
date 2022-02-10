# Report

A partire da un documento, contenente almeno una riga, è possibile generare un report in formato PDF che ne visualizzi le informazioni.\
Per poter generare un report devono essere stati definiti dei tipi di report nella Console di Amministrazione.\
Le informazioni necessarie alla configurazione di un tipo report sono:

* Codice
* Descrizione
* File template .rpx che deve essere situato nella directory \
  " 'smart mobile'/server/Documents/Reports"
* Contesto del Report (Es. Document)
* Modalità di stampa: Empty, VariableItems, GroupedByManufacturer\


Il modello delle informazioni da visualizzare è definito nei file template  .rpx, rivolgersi al [supporto tecnico](../../contatti.md) per personalizzazioni.\
Il report generato sarà visualizzato in preview nella schermata di invio report tramite mail.\
In questa schermata viene richiesto di inserire gli indirizzi di destinazione separati da una ',' oppure un ';' prima di procedere all'invio.

![](../../.gitbook/assets/simulator-screen-shot-ipad-6th-generation-2019-08-20-at-14.58.15\_framed.png)

\
È possibile che oltre agli indirizzi specificati, in automatico il report venga inviato ad ulteriori destinatari specificati nelle Impostazioni Server.\
I parametri di invio mail utilizzati sono quelli definiti nelle Impostazioni Server, è possibile configurare ogni singolo utente per far si che utilizzi la propria mail piuttosto che quella delle altre mail inviate da Kimo([Impostazioni Server](../../impostazioni/impostazioni-di-sistema.md)).

\
La condivisione del file PDF generato può avvenire anche attraverso la funzionalità di condivisione iOS accessibile dal pulsante posto in alto a destra.\


{% hint style="info" %}
Questa funzionalità è disponibile solo online, in quanto il file PDF viene generato lato server
{% endhint %}

###
