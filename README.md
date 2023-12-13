# Analisi dei Dati degli Appartamenti su Airbnb nelle Capitali Europee
Questo progetto si concentra sull'analisi esaustiva dei dati riguardanti gli appartamenti disponibili su Airbnb nelle principali capitali europee. Lo scopo primario è analizzare e comprendere i modelli di prezzo, prenotazione e occupazione, sia nei giorni feriali che durante i fine settimana.

## Panoramica del Progetto
La ricerca dei dati è stata condotta attraverso una selezione accurata di dataset provenienti da fonti autorevoli e affidabili online. Ogni capitale europea è stata rappresentata da due insiemi di dati distinti: uno relativo ai periodi dei fine settimana e l'altro riguardante i giorni lavorativi.

Il processo di aggregazione e manipolazione dei dati è stato eseguito tramite BigQuery utilizzando il linguaggio SQL. La fusione dei vari dataset ha portato alla creazione di un file consolidato denominato "TOTAL DAYS", contenente una vasta gamma di informazioni raccolte dai dati originali.

Successivamente, sfruttando le potenzialità di Python, sono stati eseguiti passaggi di pulizia dei dati e un'analisi dettagliata della correlazione tra le variabili presenti nei dataset. Questo approfondimento ha permesso di identificare tendenze significative, correlazioni tra parametri e modelli comportamentali degli utenti.

## Struttura della Repository
**input**: Contiene i dataset iniziali acquisiti da fonti attendibili e pertinenti.

**output**: Contiene il file "TOTAL DAYS", risultato della manipolazione e unione dei dati per l'analisi in Python. Contiene anche il file **"Analisi 2"**, ottenuto dopo la pulizia e l'organizzazione dei dati derivati da "TOTAL DAYS" durante l'analisi in Python. Questo file è stato preparato appositamente per l'utilizzo futuro nella creazione di una **dashboard** su Tableau.

**query**: Contiene il documento di testo con le query SQL utilizzate su BigQuery per l'elaborazione dei dati.
