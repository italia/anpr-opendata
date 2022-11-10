# Formato dati del trend mensile dei certificati richiesti

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** certificati_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese di riferimento nel calendario              | numero                   | 10       |
| **anno**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **tipo soggetto**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR) o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **tipologia certificato**      | tipologia del certificato anagrafico emesso| stringa    | Contestuale   |
| **bollo**      | numero di certificati emessi con imposta di bollo nel periodo di riferimento| numero    | 100   |
| **carta libera**      | numero di certificati emessi in carta libera nel periodo di riferimento| numero    | 100   |
| **totale**      | numero totale di certificati emessi nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No