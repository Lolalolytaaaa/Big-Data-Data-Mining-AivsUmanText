# Big-Data-Data-Mining-AivsUmanText

Questo repository contiene il progetto finale per il corso di Laboratorio di big data, data mining e data analytics.
L'obiettivo è sviluppare un modello capace di distinguere tra testi scritti da persone e testi generati da intelligenze artificiali.  
Abbiamo scelto questo tema per analizzare come i modelli linguistici moderni creano pattern ripetitivi rispetto alla variabilità della scrittura umana.
Per farlo, abbiamo utilizzato il dataset incluso in questo repository in formato .csv.

Come richiesto dalle specifiche del corso, il progetto è stato realizzato interamente in Python (formato .ipynb) utilizzando le seguenti librerie: 
-Pandas e NumPy (per la pulizia dati e il calcolo di nuove metriche testuali)
-Statsmodels (per l'analisi statistica e la validazione dei predittori)
-Scikit-learn (per gestire il dataset e la valutazione del modello) 
-TensorFlow (per creare la rete neurale LSTM).

L'analisi segue un flusso logico preciso: partendo dal caricamento dei dati, si va poi ad una fase di analisi statistica per giustificare le scelte del modello, 
arrivando infine all'addestramento della rete neurale e alla verifica dei risultati tramite matrice di confusione.
