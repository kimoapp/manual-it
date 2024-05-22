# B2b

| Valore | Descrizione |
| :--- | :--- |
| [**B2bSiteVirtualDirectoryName**](b2b.md#b2bsitevirtualdirectoryname) | Nome del sito b2b su IIS |
| [**FiltersPreserveMode**](b2b.md#filterspreservemode) | Indica se i filtri avanzati vanno mantenuti o resettati quando si effettua una nuova ricerca dalla barra di ricerca |
| [**IsGuestModeEnabled**](b2b.md#isguestmodeenabled) | Indica se è permessa la navigazione come utente 'guest' \(non autenticato\) nel B2B |
| [**IsUserSlaveModeEnabled**](b2b.md#isuserslavemodeenabled) | Indica che gli utenti B2B non sono gestiti in Kimo, ma da un sistema esterno, per cui certe operazioni sono disabilitate \(es. l'utente non può resettare la password in Kimo\) |
| [**MaxDaysWithoutOrdersBeforeDeactivation**](b2b.md#maxdayswithoutordersbeforedeactivation) | Indica il numero di giorni in cui un utente B2B può restare attivo senza ricevere ordini da parte sua |
| [**PromotionsMode**](b2b.md#promotionsmode) | Indica se le promozioni sono abilitate o meno nel B2B |
| [**SafeDaysAfterActivation**](b2b.md#safedaysafteractivation) | Indica il numero di giorni in cui un utente B2B dopo essere stato attivato non deve venir disattivato a causa dei mancati ordini |

## B2bSiteVirtualDirectoryName

**Tipo:** String

## FiltersPreserveMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Clear
* 1 =&gt; Preserve

## IsGuestModeEnabled

**Tipo:** Boolean

## IsUserSlaveModeEnabled

**Tipo:** Boolean

## MaxDaysWithoutOrdersBeforeDeactivation

**Tipo:** Int32

## PromotionsMode

**Tipo:** Enum  
**Valore di default:** 0  
**Valori:**

* 0 =&gt; Disabled
* 1 =&gt; Enabled

## SafeDaysAfterActivation

**Tipo:** Int32
