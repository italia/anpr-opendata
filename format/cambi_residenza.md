# Formato dati del trend mensile delle dichiarazioni dei cambi di residenza effettuate sia da Portale ANPR sia da Comune

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** cambi_residenza.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese di riferimento nel calendario             | numero                   | 10       |
| **ANNO**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **PARTENZA**      | regione o stato estero di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (gli stati esteri sono raggruppati nel cluster 'estero') |   stringa | Lazio  |
| **COD_ISTAT_REGIONE_DI_PARTENZA**      | codice istat della regione di residenza da cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **ARRIVO**      | regione verso cui sono state inviate le dichiarazioni di cambi di residenza| stringa             | Lombardia   |
| **COD_ISTAT_REGIONE_DI_ARRIVO**      | codice istat della regione di residenza verso cui sono state inviate le dichiarazioni di cambi di residenza (per gli stati esteri sono stati riportati i codici istat della regione proprietaria della scheda) |   stringa | 01  |
| **TOTALE**      | numero totale di dichiarazioni di cambi di residenza effettuati sia da portale ANPR che da comune nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
