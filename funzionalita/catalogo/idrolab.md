# Idrolab

L'integrazione dei cataloghi Idrolab permette di visualizzarne la scheda articolo online all'interno di Kimo.\
Per integrare Idrolab in Kimo è necessario specificare, tra le apposite [Regole di Business](../../impostazioni/business-rules/), il server e le credenziali di accesso.\
In fase di integrazione sarà necessario specificare nella tabella Manufacturer, nel campo ExternalId il codice del produttore Idrolab associato al codice produttore dell'Erp, ad esempio:

{% hint style="success" %}
Un produttore nell'Erp potrebbe avere un codice diverso da quello presente su Idrolab.\
Nel campo Manufacturer.Id va inserito il codice dell'Erp mentre nel campo Manufacturer.ExternaId il codice su Idrolab.
{% endhint %}

È necessaria anche una modifica nella tabella Item:

Il campo ManufacturerId deve essere valorizzato con il codice del produttore in Kimo (Campo Id della tabella Manufacturer) e ManufacturerItemId deve essere valorizzato con il codice dell'articolo di Idrolab.



Dopo aver eseguito le configurazioni indicate, accedendo all'app SFA sarà possibile visualizzare uno scenario aggiuntivo all'interno del dettaglio articolo; in questo scenario verrà visualizzata la scheda articolo Idrolab.\
.