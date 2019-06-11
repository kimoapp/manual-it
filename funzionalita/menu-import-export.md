# Menù Import/Export

Il menù Import/Export è visibile nella parte in alto a destra dello schermo.

![](../.gitbook/assets/menu-import-export.PNG)

### Import

![](../.gitbook/assets/image%20%283%29.png)

* Importo completo: effettua i 3 step sotto riportati. 
* Step 1: Import da Erp a KimoIntegrator. I dati presenti nell'Erp vengono importati nel database di KimoIntegrator.
* Step 2: Caricamento da KimoIntegrator. I dati presenti nel database di KimoIntegrator vengono caricati nel database di Kimo.
* Step 3: Preparazione dati di Sync. I dati presenti nel database di Kimo vengono preparati nel formato adatto ai KimoClient.
* Step 2+3: Caricamento +  Preparazione dati di Sync: esegue gli step 2 e 3.
* Importazione file immagini articoli: le immagini associate agli articoli vengono importate e copiate nella cartella \public da cui KimoClient le legge.
* Download immagini da url: i file relativi alle immagini degli articoli vengono scaricati dall'url specificata.
* Geocodifica Account: se è stato configurato l'utilizzo dell'API di Google per la geocodifica con questa funzionalità vengono recuperate le coordinate geografiche per tutti i Clienti e le Destinazioni merci presenti in Kimo.

### Import per entità

![](../.gitbook/assets/import-per-entita.PNG)

* Preparazione dati di Sync delle sole impostazioni: viene eseguita la preparazione di dati dei soli dati relativi alle impostazioni
* Import completo \(entità specifiche\): viene eseguita l'importazione completa delle sole entità specificate nella maschera proposta  ![](../.gitbook/assets/import-da-entita-specifica.PNG) 
* Step 1: Import da Erp a KimoIntegrator \(entità specifiche\): viene eseguita l'importazione delle sole entità specificate nella maschera proposta
* Step 2: Caricamento da KimoIntegrator \(entità specifiche\): viene eseguito il caricamento delle sole entità specificate nella maschera proposta
* Step 3: Preparazione dati di Sync \(entità specifiche\): viene eseguita la preparazione dei dati di Sync delle sole entità specificate nella maschera proposta
* Step 2+3: Caricamento +  Preparazione dati di Sync \(entità specifiche\): vengono eseguiti gli step 2 e 3 per le sole entità specificate nella maschera proposta.

### Export

![](../.gitbook/assets/image%20%2824%29.png)



* Export verso Erp: vengono inviati i dati da KimoIntegrator al sistema informativo.

### Administrator

![](../.gitbook/assets/administrator.PNG)

* Cambio password: consente di modificare la password dell'utente collegato.
* Logout: chiude la sessione corrente ed esce da Kimo.

