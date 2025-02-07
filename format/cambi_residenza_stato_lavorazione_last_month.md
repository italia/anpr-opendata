# Formato dati del trend del mese corrente di cambi di residenza effettuati da portale ANPR per stato di lavorazione della pratica

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** cambi_residenza_per_stato_lavorazione_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese corrente nel calendario non completo              | numero                   | 10       |
| **ANNO**  | anno corrente nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino. I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **STATO_DI_LAVORAZIONE**      | stato di lavorazione della dichiarazione di cambio di residenza| stringa    | Accolta   |
| **TOTALE**      | numero totale di dichiarazioni di cambi di residenza effettuati da portale ANPR nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
