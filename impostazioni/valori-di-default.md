# Valori di default

Un valore di default definisce il valore da assegnare ad un campo di una entità, quando ne viene eseguita la creazione da parte di un utente. Ad esempio, può essere utilizzato per impostare che quando viene creato un cliente, il campo relativo alla valuta assuma il valore 'EURO' \(corrispondente al codice della valuta\).

![](../.gitbook/assets/image%20%2836%29.png)

Il valore assunto da ciascun campo può essere personalizzato per utente.

È possibile far sì che, quando si creano certi tipi di entità, alcuni dei valori siano impostati copiando i valori di un'altra entità di partenza.  
Ad esempio, si può far sì che, creando un'offerta o un ordine, degli ulteriori campi \(es. i campi "liberi"\) vengano copiati dal cliente \(oltre ai campi che già normalmente vengono presi dal cliente per inizializzare i documenti di vendita, come il metodo di pagamento o il listino\).   
Un altro tipico caso di utilizzo è relativo alla creazione dei documenti di vendita a partire dai documenti da Erp, utilizzando dei campi di questi ultimi per inizializzare alcuni valori del nuovo documento di vendita \(o delle sue righe\). 

La sintassi per specificare che la sorgente del valore è un campo di una entità è la seguente: 

${&lt;entità&gt;.&lt;campo&gt;}

es. ${Account.FreeBoolean1}

Per ciascun entità da valorizzare è possibile specificare solo un sottoinsieme di entità da usare come sorgente.

| Entità | Entità  sorgente |
| :--- | :--- |
| Document | Account |
| DocumentLine | Account |
| DocumentLine | Item |
| DocumentFromErpDocument | ErpDocument |
| DocumentFromErpDocument | Account |
| Cart | Account |

  












