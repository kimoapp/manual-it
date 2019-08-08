---
description: Utente di tipo Cliente
---

# API: Creare un utente per B2B

{% api-method method="post" host="http://kimo.thormax.it/api/UserPublic/CreateAndActivateB2bUser" path="" %}
{% api-method-summary %}
CreateAndActivateB2bUser
{% endapi-method-summary %}

{% api-method-description %}
API per la creazione e attivazione di un Utente di tipo Cliente con accesso all'app B2B
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Inserire le credenziali di un Utente di tipo Direzionale
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="mail" type="string" required=true %}
Indirizzo mail dell'utente
{% endapi-method-parameter %}

{% api-method-parameter name="warehouseId" type="string" required=false %}
Id del magazzino da associare all'utente B2B
{% endapi-method-parameter %}

{% api-method-parameter name="role" type="string" required=true %}
Id del ruolo per utenti B2B da utilizzare in Kimo
{% endapi-method-parameter %}

{% api-method-parameter name="lastName" type="string" required=false %}
Cognome dell'utente
{% endapi-method-parameter %}

{% api-method-parameter name="firstName" type="string" required=true %}
Nome dell'utente
{% endapi-method-parameter %}

{% api-method-parameter name="password" type="string" required=true %}
password da utilizzare come credenziale di accesso all'app
{% endapi-method-parameter %}

{% api-method-parameter name="username" type="string" required=true %}
Nome utente da utilizzare per l'accesso all'app
{% endapi-method-parameter %}

{% api-method-parameter name="shipmentSiteIds" type="array" required=false %}
Array di stringhe contenente le Destinazioni Merci da associare all'Utente B2B
{% endapi-method-parameter %}

{% api-method-parameter name="accountId" type="string" required=true %}
Codice del Cliente da associare all'utente B2B
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
L'utente è stato creato e attivato con successo
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=500 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
È necessario specificare un coice cliente
Il codice cliente inserito non è stato trovato
Destinazione Merci non associa al Cliente
Il codice inserito non corrisponde ad una Destinazione Merci
Destinazione Merci non trovata
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



