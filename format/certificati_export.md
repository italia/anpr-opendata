# Formato dati del trend mensile dei certificati richiesti

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** certificati_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese di riferimento nel calendario              | numero                   | 10       |
| **ANNO**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR) o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **TIPOLOGIA_CERTIFICATO**      | tipologia del certificato anagrafico emesso| stringa    | Contestuale   |
| **BOLLO**      | numero di certificati emessi con imposta di bollo nel periodo di riferimento| numero    | 100   |
| **ESENTI_DA_BOLLO**      | numero di certificati emessi in carta libera nel periodo di riferimento| numero    | 100   |
| **TOTALE**      | numero totale di certificati emessi nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
Sono inclusi anche i certificati emessi dal servizio per gli avvocati.
