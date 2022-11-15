[![Frictionless](https://github.com/italia/anpr-opendata/actions/workflows/frictionless.yaml/badge.svg)](https://repository.frictionlessdata.io/pages/dashboard.html?user=italia&repo=anpr-opendata&flow=frictionless)


# ANPR open data

# Descrizione

Questa repository contiene i dati pubblici estratti dal portale [Anagrafe Nazionale](https://stat-int.anpr.interno.it/anpr-stat-numeri/). 

I dati dei servizi anagrafici al cittadino sono rappresentati con cadenza mensile, da quando il servizio anagrafico è reso disponibile al cittadino sul portale Anagrafe Nazionale.
Il dato popolazione e il dato di accesso al portale sono rappresentati giornalmente.

Tutti i dati contenuti nel repository sono aggiornati ogni giorno alle 6:00 (UTC).

# Contenuto

- [Struttura Repository](#struttura-repository)
- [Formato Dati](#formato-dati)
- [Aggiornamento Dati](#aggiornamento-dati)
- [Changelog](#changelog)
- [Licenza](#licenza)

# Struttura Repository

La repository è strutturata in principalmente in 4 cartelle, secondo lo schema seguente:

```
.
├── data
│   ├── accessi_export.csv
│   ├── accessi_export.json
│   ├── attivita_export.csv
│   ├── attivita_export.json
│   ├── attivita_last_month.csv
│   ├── attivita_last_month.json
│   ├── cambi_residenza_export.csv
│   ├── cambi_residenza_export.json
│   ├── cambi_residenza_last_month.csv
│   ├── cambi_residenza_last_month.json
│   ├── certificati_export.csv
│   ├── certificati_export.json
│   ├── certificati_last_month.csv
│   ├── certificati_last_month.json
│   ├── popolazione_export.csv
│   ├── popolazione_export.json
│   ├── README.md
│   ├── rettifiche_export.csv
│   ├── rettifiche_export.json
│   ├── rettifiche_last_month.csv
│   ├── rettifiche_last_month.json
│   ├── tipologia_cambi_residenza_export.csv
│   ├── tipologia_cambi_residenza_export.json
│   ├── tipologia_cambi_residenza_last_month.csv
│   ├── tipologia_cambi_residenza_last_month.json
│   ├── visure_autocertificazioni_export.csv
│   ├── visure_autocertificazioni_export.json
│   ├── visure_autocertificazioni_last_month.csv
│   └── visure_autocertificazioni_last_month.json
├── datapackage.json
├── datapackage.yaml
├── format
│   ├── accessi_export.md
│   ├── attivita_export.md
│   ├── attivita_last_month.md
│   ├── cambi_residenza_export.md
│   ├── cambi_residenza_last_month.md
│   ├── certificati_export.md
│   ├── certificati_last_month.md
│   ├── popolazione_export.md
│   ├── rettifiche_export.md
│   ├── rettifiche_last_month.md
│   ├── tipologia_cambi_residenza_export.md
│   ├── tipologia_cambi_residenza_last_month.md
│   ├── visure_autocertificazioni_export.md
│   └── visure_autocertificazioni_last_month.md
├── LICENSE
├── metadata
│   ├── dcat-ap.rdf
│   └── README
└── README.md
```

# Formato Dati

- [Trend giornaliero della tipologia di accesso al portale](https://github.com/italia/anpr-opendata/blob/main/format/accessi_export.md)
- [Trend mensile della distribuzione dell'utilizzo dei servizi](https://github.com/italia/anpr-opendata/blob/main/format/attivita_export.md)
- [Trend del mese corrente della distribuzione dell'utilizzo dei servizi](https://github.com/italia/anpr-opendata/blob/main/format/attivita_last_month.md)
- [Trend mensile delle dichiarazioni dei cambi di residenza](https://github.com/italia/anpr-opendata/blob/main/format/cambi_residenza_export.md)
- [Trend del mese corrente delle dichiarazioni dei cambi di residenza](https://github.com/italia/anpr-opendata/blob/main/format/cambi_residenza_last_month.md)
- [Trend mensile dei certificati richiesti](https://github.com/italia/anpr-opendata/blob/main/format/certificati_export.md)
- [Trend del mese corrente dei certificati richiesti](https://github.com/italia/anpr-opendata/blob/main/format/certificati_last_month.md)
- [Trend giornaliero della popolazione in ANPR](https://github.com/italia/anpr-opendata/blob/main/format/popolazione_export.md)
- [Trend mensile delle rettifiche richieste](https://github.com/italia/anpr-opendata/blob/main/format/rettifiche_export.md)
- [Trend del mese corrente delle rettifiche richieste](https://github.com/italia/anpr-opendata/blob/main/format/rettifiche_last_month.md)
- [Trend mensile delle tipologie di cambi di residenza](https://github.com/italia/anpr-opendata/blob/main/format/tipologia_cambi_residenza_export.md)
- [Trend del mese corrente delle tipologie di cambi di residenza](https://github.com/italia/anpr-opendata/blob/main/format/tipologia_cambi_residenza_last_month.md)
- [Trend mensile delle visure e delle autocertificazioni richieste](https://github.com/italia/anpr-opendata/blob/main/format/visure_autocertificazioni_export.md)
- [Trend del mese corrente delle visure e delle autocertificazioni richieste](https://github.com/italia/anpr-opendata/blob/main/format/visure_autocertificazioni_last_month.md)

Nella repository si possono trovare le tabelle, in formato .json e .csv, relative ai dati di utilizzo del portale Anagrafe Nazionale e dei relativi servizi anagrafici disponibili ai cittadini.

# Aggiornamento Dati

Tutti i dati presenti vengono aggiornati: ogni giorno alle 6:00 (UTC).

# Changelog

Le modifiche alla repository saranno tracciate in dettaglio nel file di changelog al fine di essere trasparenti riguardo l'evoluzione del contenuto e della struttura della repository. Per completezza, nel file è specificata anche la lista delle integrazioni future pianificate.

# Licenza 

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />

Nella più ampia misura permessa dalla legge, il [Ministero dell'Interno](https://www.interno.gov.it/it) ha rinunciato, ad ogni Diritto d'Autore e Connesso, e ad ogni relativa pretesa su [Anagrafe Nazionale Open data](https://stat-int.anpr.interno.it/anpr-stat-numeri/).

## Authors / Copyright

CC0 Ministero dell’Interno

## Dettagli Licenza

La licenza di questa repository è una CC0-1.0 (Creative Commons Pubblico Dominio 1.0 Universal).
Far riferimento al file [LICENSE](https://github.com/italia/anpr-opendata/blob/main/LICENSE) per il dettaglio della licenza.

## In caso di attribuzione

Seppure non richiesto, è apprezzato un riferimento alla provenienza dei dati in caso di loro riutilizzo, "Dati dalla sezione “Numeri” del portale Anagrafe Nazionale - CC0 Ministero dell’Interno"
