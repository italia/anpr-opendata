# Formato dati del trend del mese corrente delle tipologie di cambi di residenza 

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** tipologia_cambi_residenza_portale_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese corrente nel calendario non completo              | numero                   | 10       |
| **anno**  | anno corrente nel calendario  |   numero     |        2021         |
| **tipo soggetto**      | tipologia della scheda del cittadino. I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **stato di lavorazione**      | stato di lavorazione della dichiarazione di cambio di residenza| stringa    | Accolta   |
| **tipologia**      | tipologia di dichiarazioni di cambio di residenza| stringa    | Stesso comune  |
| **totale**      | numero totale di dichiarazioni di cambi di residenza effettuati da portale ANPR nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No