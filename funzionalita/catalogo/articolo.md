---
description: Funzionalità relative all'Articolo
---

# Articolo

Gli attributi base dell'Articolo sono quelli presenti nell'entità [Item](../../integrazione/database-schema/item.md).

Altre entità relazionate all'Articolo sono:

| Entità                                                                                         | Descrizione                                                             |
| ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [ItemAssociated](../../integrazione/database-schema/itemassociated.md)                         | Articoli alternativi, sostitutivi o collegati                           |
| [ItemAttachment](../../integrazione/database-schema/itemattachment.md)                         | Allegati articoli                                                       |
| [ItemCharge](../../integrazione/database-schema/itemcharge.md)                                 | Spese per articoli                                                      |
| [ItemChargeType](../../integrazione/database-schema/itemchargetype.md)                         | Tipi di spese per articoli (es. RAEE)                                   |
| [ItemCollection](../../integrazione/database-schema/itemcollection.md)                         | Collezione articoli                                                     |
| [ItemCost](../../integrazione/database-schema/itemcost.md)                                     | Costo articoli (netto, lordo, ...)                                      |
| [ItemDiscountGroup](../../integrazione/database-schema/itemdiscountgroup.md)                   | Gruppi sconti articoli                                                  |
| [ItemGroup](../../integrazione/database-schema/itemgroup.md)                                   | Gruppi merceologici                                                     |
| [ItemGroupTranslation](../../integrazione/database-schema/itemgrouptranslation.md)             | Traduzioni in lingua dei gruppi merceologici                            |
| [ItemImage](../../integrazione/database-schema/itemimage.md)                                   | Immagini articoli (percorsi dei file)                                   |
| [ItemLine](../../integrazione/database-schema/itemline.md)                                     | Linea articolo                                                          |
| [ItemListPrice](../../integrazione/database-schema/itemlistprice.md)                           | Prezzi per articolo                                                     |
| [ItemLotOfflineAvailability](../../integrazione/database-schema/itemlotofflineavailability.md) | Disponibilità 'offline' dei lotti                                       |
| [ItemOfflineAvailability](../../integrazione/database-schema/itemofflineavailability.md)       | Disponibilità 'offline' degli articoli                                  |
| [ItemSeries](../../integrazione/database-schema/itemseries.md)                                 | Serie articolo                                                          |
| [ItemSpecification](broken-reference)                                                          | Specifiche tecniche degli articoli                                      |
| [ItemSpecificationValue](../../integrazione/database-schema/itemspecificationvalue.md)         | Valori delle specifiche tecniche degli articoli                         |
| [ItemTranslation](../../integrazione/database-schema/itemtranslation.md)                       | Traduzioni in lingua dei FreeLookup                                     |
| [ItemUom](../../integrazione/database-schema/itemuom.md)                                       | Unità di misura degli articoli                                          |
| [ItemUrl](../../integrazione/database-schema/itemurl.md)                                       | Risorse 'online' degli articoli (schede tecniche online, immagini, ...) |
| [ItemVariable](../../integrazione/database-schema/itemvariable.md)                             | Varianti articolo                                                       |

### Schede Articolo

Aprendo un articolo è possibile visualizzare le seguenti tipologie di schede informative:

* Kimo: scheda articolo visualizzata di default in Kimo. La scheda può essere personalizzata intervenendo sul Layout [ItemForm](../../interfaccia-utente/sfa/layout/list/itemformcontext.md).
* Idrolab: scheda articolo Idrolab.
* Online: scheda articolo accessibile online attraverso un url. La funzionalità ha come requisito il popolamento della tabella [ItemUrl](../../integrazione/database-schema/itemurl.md) da parte dell'Erp. Nella tabella ItemUrl per ciascun codice articolo è presente un record con il link alla scheda online.

### Disponibilità

Esistono due gestioni della disponibilità: &#x20;

* [Offline](../../integrazione/database-schema/itemofflineavailability.md): è la disponibilità visualizzata di default da Kimo e fa riferimento all'ultimo dato ricevuto dall' Erp. L' Entità in cui viene memorizzata la disponibilità è [ItemOffLineAvailability](../../integrazione/database-schema/itemofflineavailability.md). La presenza di campi di tipo [ErpStatus](../../impostazioni/stati-erp.md) consente di visualizzare la disponibilità graficamente usando icone FontAwesome.&#x20;
* Online: in Kimo è possibile richiedere all'Erp la disponibilità aggiornata: questa informazione aggiorna il valore della disponibilità offline. Questa funzionalità richiede la connessione attiva ([contattare il supporto tecnico](../crm/contatti.md)). \
  Per abilitare questa funzionalità è necessaria una configurazione a livello di integrazione Erp.\
  La funzionalità è riservata agli utenti con Ruolo di tipo Agente  e con l'autorizzazione ["Può vedere la disponibilità online"](../../impostazioni/ruoli.md#definizione-di-un-ruolo-per-agenti) attiva.

## Immagini

Per ciascun Articolo possono essere associate una o più immagini.\
Il nome del file immagine deve essere specificato nell'entità ItemImage.\
Le immagini debbono risiedere nella cartella specificata nelle [Impostazioni di sistema](../../impostazioni/impostazioni-di-sistema.md#impostazioni-itemsimage): il valore da utilizzare è "ItemsImages\SourceDirectory".

Le immagini vengono possono essere visualizzate su: Catalogo, Scheda articolo, riga Documenti di vendita, riga Documenti Erp.

Su SFA le immagini vengono possono essere scaricate in fase di Sincronizzazione ma non è necessario eseguire la fase di "Preparazione Sync".

## Varianti

Il campo Item.TypeId con valore 3 indica che l'Articolo presenta delle Varianti.\
E' possibile inserire per ogni Articolo fino a 2 tipi di varianti (Es. Colore, Taglia).\
Le varianti degli Articoli devono necessariamente essere presenti tra le anagrafiche di Kimo, altrimenti non verranno riconosciute e verrà segnalato un errore nei vari moduli.\
In fase di inserimento ordine, per gli articoli a variante, viene proposto un editor della riga che facilita la selezione delle varianti e l'inserimento delle quantità di vendita.\
Nelle editor della riga documento, per gli articoli a variante, è possibile visualizzare la disponibilità per ogni coppia di variante\
\
Esempio

* Articolo: x Variante1: rosso, Variante2: 37 disponibilità 30
* Articolo: x Variante1: giallo, Variante2: 41 disponibilità 25

### Allegati

Nella tabella [ItemAttachment](../../integrazione/database-schema/itemattachment.md) è possibile specificare i nomi dei file da associare al codice articolo. Questi file devono essere presenti nel percorso base specificato nell'apposita [Impostazione di Sistema.](../../impostazioni/impostazioni-di-sistema.md#impostazioni-filetypeid)\
I tipi di file supportati sono tutti quelli accessibili da iPad.\
Gli allegati di un articolo saranno visualizzabili, come elenco, in uno scenario aggiuntivo presente all'interno dell dettaglio articolo.\
Cliccando in ogni singolo elemento dell'elenco verrà visualizzato il relativo file.

## Articoli associati

| Tipologia   | Icona                                                                                    | Descrizione                                                         |
| ----------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Correlati   |  <img src="../../.gitbook/assets/relateditems-2x.png" alt="" data-size="original">       | Articoli che potrebbero essere venduti insieme Es. Bundle.          |
| Alternativi | <img src="../../.gitbook/assets/alternativeitems-2x.png" alt="" data-size="original">    | Articoli con le stesse caratteristiche dell'articolo di riferimento |
| Sostitutivi |  <img src="../../.gitbook/assets/substitutiveitems-2x.png" alt="" data-size="original">  |   Articoli che andranno a sostituire il modello precedente          |
.