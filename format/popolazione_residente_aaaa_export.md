# Formato dati dell'andamento mensile della popolazione residente per comune in ANPR in riferimento all'anno del file

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** popolazione_residente_aaaa_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese di riferimento nel calendario             | numero                   | 10       |
| **ANNO**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **REGIONE**       | regione di residenza | stringa             | LAZIO             |
| **PROVINCIA**       | provincia di residenza | stringa             | ROMA             |
| **COD_ISTAT_COMUNE**       | codice ISTAT del comune di residenza | stringa             | 001229             |
| **COMUNE**       | comune di residenza | stringa             | ROMA           |
| **RESIDENTI**       | numero di residenti sulla base della regione, provincia e/o comune di riferimento  | numero             | 60000            |


Questi dati sono disponibili anche in formato json.

### Note
Verrà generato un'export per ogni anno, a partire dal 2022, dentro la cartella "stats".
