# AI vs Human Text: Analisi a due livelli e classificazione tramite Deep Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Numpy%20%7C%20Scikit--Learn-orange.svg)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-red.svg)
![Statsmodels](https://img.shields.io/badge/Stats-Statsmodels-lightblue.svg)

## Introduzione e motivazioni
L'obiettivo del presente progetto è analizzare un dataset di testi e costruire un classificatore capace di distinguere tra **testi scritti da umani** e **testi generati da intelligenze artificiali**.

L'analisi confronta due approcci distinti:
* **Approccio statistico:** basato su feature strutturali del testo (lunghezza del testo, conteggio parole, lunghezza media delle parole).
* **Approccio sequenziale:** basato su reti neurali **LSTM** per catturare pattern linguistici complessi e dipendenze a lungo raggio[cite: 85].
Il progetto dimostra come l'approccio basato su Deep Learning sia estremamente efficace nel riconoscere pattern ripetitivi tipici dell'AI, superando i limiti della separazione lineare dei modelli statistici classici.

## Workflow
1.  **Pulizia e preparazione dei dati:** rimozione valori nulli e gestione righe malformate.
2.  **Feature Engineering:** creazione di metriche numeriche sulla struttura del testo tramite NumPy.
3.  **Analisi di primo livello (Statistica):** validazione dei predittori tramite modelli Logit[cite: 71].
4.  **Analisi di secondo livello (Deep Learning):** tokenizzazione, padding e addestramento rete neurale LSTM[cite: 83, 84, 85].
5.  **Valutazione:** analisi delle performance tramite matrice di confusione e report di classificazione[cite: 95, 96].

## Strumenti
* **Python:** (Pandas, Numpy, Scikit-learn, Seaborn/Matplotlib)[cite: 1].
* **Statsmodels:** per la regressione logistica e test di significatività[cite: 71].
* **TensorFlow/Keras:** per lo sviluppo dell'architettura LSTM[cite: 8, 85].

## Risultati
* **Analisi Statistica:** Il modello Logit ha evidenziato una "Perfect Separation", suggerendo che le feature strutturali sono indicatori forti ma necessitano di modelli più complessi per una generalizzazione robusta[cite: 77, 80].
* **Performance Deep Learning:** La rete LSTM ha raggiunto un'accuratezza del **100%** sul test set, dimostrando una perfetta capacità di discriminazione sulle classi analizzate.

## Fonti e bibliografia
![Dataset](https://img.shields.io/badge/Dataset-Available-blue)
![Kaggle](https://img.shields.io/badge/Source-Kaggle-brightgreen)

**AI vs Human Text Dataset**
Dataset contenente circa 500k testi etichettati per il rilevamento di contenuti generati da AI: [Link al Dataset su Kaggle](https://www.kaggle.com/code/mukaffimoin/ai-vs-human-text-detection/notebook)[cite: 18].

---
**Scotti Laura e Diarciuc Ana Maria**, Tecnologie dei Sistemi Informatici - Big Data, Data Mining e Data Analytics
