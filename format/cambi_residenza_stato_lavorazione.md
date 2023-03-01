# Formato dati del trend mensile di cambi di residenza effettuati da portale ANPR per stato di lavorazione della pratica

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** cambi_residenza_per_stato_lavorazione.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese di riferimento nel calendario              | numero                   | 10       |
| **anno**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **tipo soggetto**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **stato di lavorazione**      | stato di lavorazione della dichiarazione di cambio di residenza| stringa    | Accolta   |
| **totale**      | numero totale di dichiarazioni di cambi di residenza effettuati da portale ANPR nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No