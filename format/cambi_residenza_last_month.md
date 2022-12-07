# Formato dati del trend del mese corrente delle dichiarazioni dei cambi di residenza

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** cambi_residenza_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese corrente nel calendario non completo             | numero                   | 10       |
| **anno**  | anno corrente nel calendario |   numero     |        2021         |
| **partenza**      | regione o stato estero di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (gli stati esteri sono raggruppati nel cluster 'estero') |   stringa | Lazio  |
| **cod istat regione di partenza**      | codice istat della regione di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **arrivo**      | regione verso cui sono state inviate le dichiarazioni di cambi di residenza| stringa             | Lombardia   |
| **cod istat regione di arrivo**      | codice istat della regione di residenza verso cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **totale**      | numero totale di dichiarazioni di cambi di residenza effettuati sia da portale ANPR che da comune nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No