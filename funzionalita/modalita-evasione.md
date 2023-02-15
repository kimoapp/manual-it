# Modalità evasione

In Kimo B2B gli utenti avranno la possibilità **** di impostare facilmente la modalità di evasione del carrello desiderata. In base ai ruoli e quindi ai permessi associati a quest'ultimo sarà possibile avere più o meno opzioni di evasione dell'ordine.

Ogni carrello/ordine prevederà al massimo queste tipologie di evasione:

* **spedizione** in una destinazione merce;
* **ritiro al banco** tra dei banchi disponibili;
* **evasione mista** quando il carrello prevede sia spedizione che ritiro al banco.

All'interno dell'area dedicata nelle informazioni del carrello l'utente avrà



**Visualizzazione dei valori selezionati**All'apertura della form, vanno mostrati come selezionati i parametri correnti.Potenzialmente ci possono essere più sorgenti per questi parametri (i valori nella testata del carrello, o i valori attuali delle righe, che sono poi gli stessi mostrati nel riepilogo del carrello).Va considerata come sorgente i parametri "effettivi", gli stessi mostrati nel riepilogo.Esempio:Un carrello ha come modalità evasione "spedizione" ma l'utente ha selezionato per tutte le righe "ritiro al banco", mettendo sempre lo stesso magazzino tranne che per una riga.Nel riepilogo viene mostrata "evasione mista".In questa form in cui vengono impostati i valori, invece, come modalità di evasione si mostra come selezionata "ritiro al banco" (valore presente in tutte le righe), mentre il magazzino non va selezionato (perché una riga ha un valore diverso dalle altre).

****

**Salvataggio nuovi valori**Nel momento in cui l’utente va a salvare le nuove impostazioni, i valori selezionati vengono impostati sia come default a livello di carrello (usandoli ogni volta viene aggiunta una nuova riga), sia vengono applicati a tutte le righe già esistenti, sovrascrivendo i valori precedenti (NON faremo una gestione più granulare, chiedendo all’utente se vuole mantenere alcune delle modifiche fatte a livello di riga).
