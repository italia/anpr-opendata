# Formato dati del trend mensile delle rettifiche richieste

## Data aggiornamento
- Ogni giorno alle 7:15 (ora locale).  

## Formato dati

**Reference file:** rettifiche_export.csv<br>

| Nome campo                  | Descrizione                       | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|-------------------------------|---------------------|
| **MESE**       | mese di riferimento nel calendario              | numero                   | 10       |
| **ANNO**  | anno di riferimento nel calendario  |   numero     |        2021         |
| **TIPO_SOGGETTO**      | tipologia della scheda del cittadino. I valori che assume possono essere Residente (residenti in Italia iscritte in ANPR)o AIRE(Italiani Residenti all'Estero)| stringa             | Residente   | 
| **TIPOLOGIA_DI_RETTIFICA**  | tipologia di richiesta di rettifica | stringa    | Residenza:Cap   |
| **STATO_DI_LAVORAZIONE**      | stato di lavorazione della richiesta di rettifica presa in carico dal comune di competenza| stringa    | Accolta   |
| **TOTALE**      | numero totale di richieste di rettifica nel periodo di riferimento| numero             | 1000   |

Questi dati sono disponibili anche in formato json.

### Note
No
