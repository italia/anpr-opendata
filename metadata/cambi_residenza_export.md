# Formato dati del trend mensile delle dichiarazioni dei cambi di residenza

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** cambi_residenza_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese di riferimento nel calendario              | numero                   | 10       |
| **anno**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **partenza**      | regione o stato estero di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (gli stati esteri sono raggruppati nel cluster 'estero') |   stringa | Lazio  |
| **cod istat regione di partenza**      | codice istat della regione di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **arrivo**      | regione verso cui sono state inviate le dichiarazioni di cambi di residenza| stringa             | Lombardia   |
| **cod istat regione di arrivo**      | codice istat della regione di residenza verso cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **totale**      | numero totale di dichiarazioni di cambi di residenza nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No