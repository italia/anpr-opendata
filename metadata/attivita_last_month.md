# Formato dati del trend del mese corrente della distribuzione dell'utilizzo dei servizi

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** attivita_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese corrente nel calendario non completo              | numero                   | 10       |
| **anno**  | anno corrente nel calendario  |   numero     |        2021         |
| **regione**      | regione di residenza dai quali vengono fruiti i servizi |   stringa | Lazio  |
| **cod istat regione**      | codice istat della regione di residenza dai quali vengono fruiti i servizi |   stringa | 01  |
| **stato estero**      | stato estero di residenza dai quali vengono fruiti i servizi |   stringa | Spagna  |
| **codice iso stato**      | codice iso dello stato estero di residenza dai quali vengono fruiti i servizi |   stringa | SPA  |
| **tipo soggetto**      | tipologia della scheda del cittadino (Residente o AIRE)| stringa             | Residente   |
| **rettifiche**      | numero di richieste di rettifiche nel periodo di riferimento.
                       Il servizio è finalizzato a richiedere la rettifica di uno o più dati registrati nella tua scheda anagrafica
					   in caso di semplice errore di digitazione o di errata trascrizione| numero             | 1000   |
| **cambi di residenza**      | numero di dichiarazioni di cambi di residenza nel periodo di riferimento.
                               Il servizio è disponibile soltanto per effettuare cambi di residenza tra comuni diversi,
							   cambi di residenza all’interno dello stesso comune, rimpatri in Italia di cittadini AIRE.| numero             | 1000   |
| **autocertificazioni**      | numero di autocertificazioni richieste nel periodo di riferimento.
                                L'autocertificazione sostituisce i certificati nelle occasioni consentite| numero             | 1000   |
| **visure**      | numero di fruitori del servizio di visura nel periodo di riferimento.
					La visura in ANPR consente al cittadino di verificare i propri dati registrati dal comune nell’anagrafe nazionale| numero             | 1000   |
| **certificati**      | numero di certificati emessi nel periodo di riferimento
					    il certificato anagrafico è un documento contenente le informazioni anagrafiche, 
						come residenza, cittadinanza, stato civile, anagrafico di nascita, stato di famiglia. 
						Si usa quando è necessario certificare più informazioni riguardanti la stessa persona| numero             | 1000   |
| **totale**      | numero totale di servizi fruiti nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No