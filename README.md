# Open Data Publication Template

Questo repository è un template, creato a partire da esperienze precedenti, come quella di https://github.com/ministero-salute/it-dgc-repository-template, con i seguenti obiettivi:
* distribuire dei dataset in uno o più formati
* con una licenza aperta
* corredati di metadati:
  * nel formato DCAT-AP_IT
  * nel formato Frictionless data
* in modo da poter essere inseriti facilmente nel portale https://dati.gov.it

## Cosa modificare

* inserire una licenza corretta nel file LICENSE
* inserire la descrizione corretta nel file datapackage.yaml, eventualmente utilizzando come base il file ottenuto con il comando `frictionless describe`
* inserire i dati mancanti all'interno della directory metadata
