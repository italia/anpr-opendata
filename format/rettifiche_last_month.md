# Formato dati del trend del mese corrente delle rettifiche richieste

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale). 

## Formato dati

**Reference file:** rettifiche_last_month.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese corrente nel calendario non completo          | numero                   | 10       |
| **ANNO**  | anno corrente nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino.I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **TIPOLOGIA_DI_RETTIFICA**  | tipologia di richiesta di rettifica | stringa    | Residenza:Cap   |
| **STATO_DI_LAVORAZIONE**      | stato di lavorazione della richiesta di rettifica presa in carico dal comune di competenza| stringa    | Accolta   |
| **TOTALE**      | numero totale di richieste di rettifica nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
