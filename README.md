# Confronto Modelli Serie Storiche: Statistici vs. LSTM

Questo repository contiene il codice sorgente, i notebook di analisi e la documentazione della tesi di laurea triennale dal titolo "Analisi comparativa di modelli di previsione di Serie Storiche".

## 📖 Descrizione

Progetto di tesi per il confronto tra modelli statistici tradizionali e modelli di Machine Learning (in particolare reti LSTM) per la previsione di serie storiche. L'analisi è applicata a un dataset di benchmark, includendo fasi di preprocessing dei dati, fine-tuning dei modelli e valutazione comparativa delle performance tramite le principali metriche.

## 🎯 Obiettivo del Progetto

Lo studio delle serie storiche è fondamentale per comprendere e prevedere l'evoluzione di fenomeni che variano nel tempo. Questa tesi si propone di analizzare e mettere a confronto due approcci principali per il *forecasting*:

1.  **Modelli Statistici Tradizionali:** Metodi consolidati che si basano su proprietà statistiche dei dati (es. autocorrelazione, stagionalità, trend).
2.  **Modelli di Deep Learning:** Nello specifico, reti neurali ricorrenti di tipo **LSTM (Long Short-Term Memory)**, note per la loro capacità di apprendere dipendenze a lungo termine.

L'obiettivo finale è valutare potenzialità e limiti di ciascun approccio sullo stesso dataset, evidenziando quale metodologia offre prestazioni migliori in termini di accuratezza della previsione.

## 🛠️ Metodologia

Il flusso di lavoro seguito in questo progetto è suddiviso nelle seguenti fasi:

1.  **Analisi Esplorativa (EDA):** Studio del dataset per identificare trend, stagionalità, rumore e altre caratteristiche.
2.  **Preprocessing dei Dati:** Applicazione di trasformazioni specifiche (es. differenziazione per modelli statistici, normalizzazione per LSTM) in modo coerente con le esigenze di ciascun modello.
3.  **Modellazione e Addestramento:**
    * Implementazione dei modelli statistici [Es. ARIMA, SARIMA, Holt-Winters...].
    * Costruzione e training della rete LSTM.
4.  **Fine-Tuning:** Ottimizzazione degli iperparametri di ciascun modello per massimizzarne le prestazioni (es. ricerca dei parametri p,d,q per ARIMA; tuning di learning rate, numero di layer, ecc. per LSTM).
5.  **Valutazione:** Confronto finale delle previsioni utilizzando sia metriche quantitative (come RMSE, MAE, MAPE) sia un'analisi grafica qualitativa.

## 📊 Dataset

Il confronto è stato condotto su un dataset di benchmark ampiamente utilizzato nel campo delle serie storiche: **ethereum_daily_data_2018_2024**.

Il dataset è disponibile nella cartella `/data`.
