---
description: API pubblica per la creazione di comunicazioni
---

# Public API

## Crea una nuova comunicazione

<mark style="color:green;">`POST`</mark> `/`api/communicationPublic/Create

L'API permette di creare una nuova comunicazione in Kimo.

**Headers**

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Basic Auth`       |

**Body**

<table><thead><tr><th width="216">Name</th><th width="279">Type</th><th>Description</th></tr></thead><tbody><tr><td>imageUrl</td><td>string</td><td>Url dell'immagine di copertina.</td></tr><tr><td>categories</td><td>string[]</td><td>Elenco categorie della comunicazione.</td></tr><tr><td>contents</td><td><a href="public-api.md#communicationcontent">CommunicationContent</a>[]</td><td>Contenuto della comunicazione, è un array per permettere la gestione in lingua.</td></tr><tr><td>recipients</td><td><a href="public-api.md#communicationrecipientrule">CommunicationRecipientRule</a>[]</td><td>Elenco delle regole di invio della comunicazione.</td></tr><tr><td>enabledForPublishing</td><td>bool</td><td>Se true la comunicazione verrà pubblicata alla creazione, altrimenti verrà solo creata ed andrà pubblicata da Kimo Webapp.</td></tr><tr><td>sendNotification</td><td>bool</td><td>Se true viene inviata la notifica push agli utenti destinatari, altrimenti non vengono eseguite azioni.</td></tr><tr><td>sendNotificationEmail</td><td>bool</td><td>Se true viene inviata la mail di notifica agli utenti destinatari, altrimenti non vengono eseguite azioni.</td></tr></tbody></table>

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
    "id": "Communication_22"
}
```
{% endtab %}

{% tab title="500" %}
```json
{
  "message": "Errore message"
}
```
{% endtab %}
{% endtabs %}



### CommunicationContent

| Name     | Type   | Description                                                                |
| -------- | ------ | -------------------------------------------------------------------------- |
| language | string | Codice lingua, le lingue gestite sono: it, en, de, fr, hu, pl, zh, jp, ru. |
| title    | string | Titolo della comunicazione mostrata su Kimo.                               |
| body     | string | Definizione del corpo della comunicazione in HTML.                         |
| visible  | bool   | Se true sarà un contenuto visualizzabile altrimenti no.                    |



### CommunicationRecipientRule

| Name    | Type      | Description                                                                                                                                                                                                                                                                                                                              |
| ------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| include | bool      | Definisce se la regola deve comportarsi in modo inclusivo o esclusivo.                                                                                                                                                                                                                                                                   |
| type    | string    | Tipologia della regola, i valori supportati sono: Accounts, SalesAgents, Roles, CustomerGroups, All, AllSalesAgents, AllAccounts.                                                                                                                                                                                                        |
| values  | string\[] | <p>In accordo con la tipologia della regola indica a quali destinatari inviare o non inviare la comunicazione.<br>Se il tipo di rule è Accounts ci aspettiamo di ricevere dei codici clienti, se rule è SalesAgents ci aspetteremo dei codici agente, ... .<br>Non ha utilità se si stanno usando All, AllSalesAgents e AllAccounts.</p> |

### Esempio richiesta

```json
{
   "imageUrl": "http://URLIMMAGINE.IT",
   "categories":[     
        "Comunicazione importante",
        "Novità"
   ],
   "contents":[
      {
         "language":"it",
         "title":"Test comunicazione italiano 4",
         "body":"<p><b>Corpo comunicazione di test<br></b></p><table class=\"table table-bordered\"><tbody><tr><td>1</td><td>2</td></tr><tr><td>3</td><td>4</td></tr><tr><td>5</td><td>6</td></tr><tr><td>7</td><td>8</td></tr></tbody></table><p><img src=\"https://immagineditest.jpg\" style=\"width: 72px;\"><b><br></b></p><p><b><br></b></p>",
         "visible":true
      },
      {
         "language":"en",
         "title":"Test comunicazione inglese 4",
         "body":"<p><b>Corpo comunicazione di test<br></b></p><table class=\"table table-bordered\"><tbody><tr><td>1</td><td>2</td></tr><tr><td>3</td><td>4</td></tr><tr><td>5</td><td>6</td></tr><tr><td>7</td><td>8</td></tr></tbody></table><p><img src=\"https://immagineditest.jpg\" style=\"width: 72px;\"><b><br></b></p><p><b><br></b></p>",
         "visible":true
      }
   ],
   "recipients":[
      {
         "include":true,
         "type":"SalesAgents",
         "values":[
            "027"
         ]
      },
      {
         "include":true,
         "type":"Accounts",
         "values":[
            "1004370"
         ]
      }
   ],
   "enabledForPublishing": true,
   "sendNotification":false,
   "sendNotificationEmail":false
}
```
