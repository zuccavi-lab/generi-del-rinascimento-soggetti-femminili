# generi-del-rinascimento-soggetti-femminili

## DOI

DOI: 10.5281/zenodo.22680607

## Descrizione
Questo progetto analizza un dataframe storico-artistico contentente una serie di quadri italiani. Dopo un'attenta analisi del dataframe mi sono focalizzata in particolare sul movimento del Rinascimento e sulle figure femminili che venivano rappresentate in alcuni generi artisici precisi.

### Quali sono i risultati?
- Nel Rinascimento, qual è stata l'evoluzione dei quadri religiosi, mitologici o dei ritratti?
- Di tutti i quadri che raffigurano donne nel Rinascimento, quanti sono di questi generi?
- E, nel corso dei secoli, come sono cambiate queste quantità?

## Fonte dei dati
Ho utilizzato il dataset storico-artistico estratto da WikiData. I dati sono stati recuperati dal repository di [GitHub di sbrzt](https://github.com/dhdmch/2025-2026/tree/main/data/vapod), sono costituiti da un file csv, formato da 12 colonne e 2444 righe.

Un esempio dei dati utilizzati è il seguente:

| Variabile | Tipo |	Definizione | Esempio |
| :------- | :--- | :--------- | :------ |
|     id | object | ID del quadro su WikiData | http://www.wikidata.org/entity/Q428274 |,
|titolo |object  |titolo dell'opera |Ritratto di Fedra Inghirami, detto Fedra|
|artisti|object|nome e genere degli artisti dell'opera|Raffaello Sanzio (maschio)|
|data_creazione|object|intervallo degni anni di creazione dell'opera|1510|
|generi|object|genere artistico dell'opera|ritratto|
|luoghi|object|luogo di conservazione attuale|Galleria Palatina|
|collezioni|object|collezioni di cui l'opera fa parte|Galleria Palatina|
|contenuti|object|contenuti rappresentati nell'opera|libro; carta; scrittura; strabismo; posizione ...|
|movimenti|object|movimento artistico di cui l'opera fa parte|Alto Rinascimento|
|soggetti|object|soggetto principale rappresentato nell'opera|Tommaso Inghirami|
|altezza|float64|altezza dell'opera, in centimetri|91.0|
|larghezza|float64|larghezza dell'opera, in centimetri|61.0|

Il dataset è disponibile su [GitHub](https://raw.githubusercontent.com/dhdmch/2025-2026/refs/heads/main/data/vapod/data.csv).

## Metodi e strumenti
I dati sono lavorati su Google Colab in questo notebook, utilizzando il linguaggio di programmazione Python e la libreria di analisi Pandas.

## Responsabili
Zucca, Virginia

## Licenza
[Creative Commons 0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
