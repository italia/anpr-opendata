# Formato dati del trend del mese corrente delle visure e delle autocertificazioni richieste

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** visure_autocertificazioni_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese corrente nel calendario non completo              | numero                   | 10       |
| **ANNO**  | anno corrente nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **AUTOCERTIFICAZIONI**      | numero di autocertificazioni richieste nel periodo di riferimento| numero    | 2000   |
| **VISURE**      | numero di fruitori del servizio di visura nel periodo di riferimento| numero    | 2000   |
| **TOTALE**      | numero totale di visure e delle autocertificazioni richieste nel periodo di riferimento| numero             | 5000   |

Questi dati sono disponibili anche in formato json.

### Note
No
