# Formato dati del trend mensile delle dichiarazioni dei cambi di residenza distinte per tipologia di canale (Portale ANPR, Comuni)

## Data aggiornamento
- Ogni giorno alle 2 (UTC). 

## Formato dati

**Reference file:** cambi_residenza_canale_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **mese**       | mese di riferimento nel calendario              | numero                   | 10       |
| **anno**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **da portale ANPR**      |  dichiarazioni di cambi di residenza effettuate da portale ANPR |   stringa | Lazio  |
| **tipo soggetto**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR) o AIRE(Italiani Residenti all'Estero) |   stringa | 01  |
| **da comuni**      | dichiarazioni di cambi di residenza effettuate da sportello comunale| stringa             | Lombardia   |

Questi dati sono disponibili anche in formato json.

### Note
No