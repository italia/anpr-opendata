# Formato dati del trend del mese corrente delle rettifiche richieste

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** rettifiche_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese corrente nel calendario non completo          | numero                   | 10       |
| **anno**  | anno corrente nel calendario  |   numero     |        2021         |
| **tipo soggetto**      | tipologia della scheda del cittadino. 
						   I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR) 
						   o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **tipologia di rettifica**  | tipologia di richiesta di rettifica | stringa    | Residenza:Cap   |
| **stato di lavorazione**      | stato di lavorazione della richiesta di rettifica presa in carico dal comune di competenza| stringa    | Accolta   |
| **totale**      | numero totale di richieste di rettifica nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No