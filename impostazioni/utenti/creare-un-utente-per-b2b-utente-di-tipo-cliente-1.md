---
description: Utente di tipo Cliente
---

# API: Creare un utente per B2B

{% swagger baseUrl="http://kimo.thormax.it/api/UserPublic/CreateAndActivateB2bUser" path="" method="post" summary="CreateAndActivateB2bUser" %}
{% swagger-description %}
API per la creazione e attivazione di un Utente di tipo Cliente con accesso all'app B2B
{% endswagger-description %}

{% swagger-parameter in="header" name="Authentication" type="string" %}
Inserire le credenziali di un Utente di tipo Direzionale
{% endswagger-parameter %}

{% swagger-parameter in="body" name="mail" type="string" %}
Indirizzo mail dell'utente
{% endswagger-parameter %}

{% swagger-parameter in="body" name="warehouseId" type="string" %}
Id del magazzino da associare all'utente B2B
{% endswagger-parameter %}

{% swagger-parameter in="body" name="role" type="string" %}
Id del ruolo per utenti B2B da utilizzare in Kimo
{% endswagger-parameter %}

{% swagger-parameter in="body" name="lastName" type="string" %}
Cognome dell'utente
{% endswagger-parameter %}

{% swagger-parameter in="body" name="firstName" type="string" %}
Nome dell'utente
{% endswagger-parameter %}

{% swagger-parameter in="body" name="password" type="string" %}
password da utilizzare come credenziale di accesso all'app
{% endswagger-parameter %}

{% swagger-parameter in="body" name="username" type="string" %}
Nome utente da utilizzare per l'accesso all'app
{% endswagger-parameter %}

{% swagger-parameter in="body" name="shipmentSiteIds" type="array" %}
Array di stringhe contenente le Destinazioni Merci da associare all'Utente B2B
{% endswagger-parameter %}

{% swagger-parameter in="body" name="accountId" type="string" %}
Codice del Cliente da associare all'utente B2B
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
L'utente è stato creato e attivato con successo
```
{% endswagger-response %}

{% swagger-response status="500" description="" %}
```
È necessario specificare un coice cliente
Il codice cliente inserito non è stato trovato
Destinazione Merci non associa al Cliente
Il codice inserito non corrisponde ad una Destinazione Merci
Destinazione Merci non trovata
```
{% endswagger-response %}
{% endswagger %}

