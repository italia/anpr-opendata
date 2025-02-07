# Formato dati della distribuzione dell'utilizzo dei servizi relativa ai soli soggetti AIRE

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale).  

## Formato dati

**Reference file:** attivita_AIRE_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **DATA_ELABORAZIONE**       | Data di elaborazione              | GG-MM-AAAA                    | 12-10-2022          |
| **STATO_ESTERO**      | stato estero di residenza dai quali vengono fruiti i servizi |   stringa | Spagna  |
| **CODICE_ISO**      | codice iso dello stato estero di residenza dai quali vengono fruiti i servizi |   stringa | SPA  |
| **RETTIFICHE**      | numero di richieste di rettifiche da inizio servizio.Il servizio è finalizzato a richiedere la rettifica di uno o più dati registrati nella tua scheda anagrafica in caso di semplice errore di digitazione o di errata trascrizione| numero             | 1000   |
| **CAMBI_RESIDENZA**      | numero di dichiarazioni di cambi di residenza da inizio servizio.Il servizio è disponibile soltanto per effettuare cambi di residenza tra comuni diversi, cambi di residenza all’interno dello stesso comune, rimpatri in Italia di cittadini AIRE.| numero             | 1000   |
| **AUTOCERTIFICAZIONI**      | numero di autocertificazioni richieste da inizio servizio. L'autocertificazione sostituisce i certificati nelle occasioni consentite| numero             | 1000   |
| **VISURE**      | numero di fruitori del servizio di visura da inizio servizio.La visura in ANPR consente al cittadino di verificare i propri dati registrati dal comune nell’anagrafe nazionale| numero             | 1000   |
| **CERTIFICATI**      | numero di certificati emessi da inizio servizio.Il certificato anagrafico è un documento contenente le informazioni anagrafiche, come residenza, cittadinanza, stato civile, anagrafico di nascita, stato di famiglia. Si usa quando è necessario certificare più informazioni riguardanti la stessa persona| numero             | 1000   |
| **TOTALE**      | numero totale di servizi fruiti| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
