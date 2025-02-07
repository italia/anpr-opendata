# Formato dati del trend mensile delle tipologie di cambi di residenza effettuate sia da Portale ANPR che da Comune

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** tipologia_cambi_residenza_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese di riferimento nel calendario              | numero                   | 10       |
| **ANNO**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **TIPOLOGIA**      | tipologia di dichiarazioni di cambio di residenza| stringa    | Stesso comune  |
| **TOTALE**      | numero totale di dichiarazioni di cambi di residenza effettuati sia da portale ANPR che da comune nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
