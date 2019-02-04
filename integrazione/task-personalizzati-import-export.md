# Task personalizzati import/export

Sia nel processo di Import dei dati dal Sistema Informativo a Kimo, sia in Export, è possibile eseguire dei task "custom". Ad esempio, in import può essere utile eseguire degli script che eseguano delle elaborazioni sui dati prima che siano importati in Kimo. In Export, invece, può essere utile per esportare i dati su canali diversi al database di integrazione "standard", ad esempio invocando dei WebService.

## Task in Import

È possibile eseguire uno script \(es. un file .bat, .cmd, .exe, ...\) in fase di Import impostando il suo percorso nell'Impostazione Server "Import\CustomTask". 

{% hint style="info" %}
La caratteristica più importante di uno script eseguito in questa modalità, rispetto ad uno script eseguito attraverso altri meccanismi \(es. un task schedulato nel sistema operativo\) è che lo script verrebbe richiamato dopo che Kimo ha già impegnato il semaforo che regola il flusso di import, quindi si eviterebbero eventuali "conflitti" con scritture da parte del Sistema Informativo.
{% endhint %}

## Task in Export

L'esecuzione di un task personalizzato in fase di export richiede la scrittura di un "plugin", una DLL contenente le istruzioni da eseguire. Tale DLL deve essere realizzata con particolari specifiche per poter essere riconosciuta da Kimo come plugin.  
Contattare il team di sviluppo di Kimo per ulteriori informazioni.

