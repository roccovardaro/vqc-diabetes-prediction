# 🩺 Predizione del Diabete – Approccio Classico e Quantistico

Questo progetto esplora diverse tecniche per la **predizione del diabete**, combinando approcci di **Machine Learning classico** con tecniche innovative di **Quantum Machine Learning (QML)**. L'obiettivo è confrontare le performance e l'efficacia dei diversi modelli nella classificazione della presenza o meno di diabete, utilizzando dataset reali.

## 📁 Struttura del Progetto

```
.
├── src/                        # Codice sorgente
│   ├── Dataset_Preprocessing.ipynb  # Preprocessing e analisi dei dataset
│   ├── ML_classification.ipynb      # Modelli di classificazione classici (ML)
│   └── VQC.ipynb                    # Quantum classifier (Variational Quantum Circuit)
│
├── dataset/                   # Dataset utilizzati
│   ├── diabetes.csv                               # Dataset principale
│   ├── final_diabetes_dataset_3.csv               # Dataset pre-processato con 3 Feature
│   ├── final_diabetes_dataset_4.csv               # Dataset pre-processato con 4 Feature
│   └── final_diabetes_dataset_5.csv               # Dataset pre-processato con 5 Feature
│
└── README.md                  
```

## 🧠 Obiettivo

L'obiettivo principale è prevedere il diabete in base a parametri medici (come glucosio, pressione sanguigna, BMI, ecc.), testando vari approcci di classificazione:

- __Modelli di Machine Learning tradizionale__ (es. Decision Tree)
- __Quantum Classifier__ (VQC - Variational Quantum Circuit)

## 📊 Dataset

Il dataset principale (`diabetes.csv`) è basato sul famoso **Pima Indians Diabetes Dataset**. Sono presenti anche versioni pre-processate in base a diverse tecniche di normalizzazione e selezione delle feature.

Caratteristiche principali:

- Numero di gravidanze
- Glucosio
- Pressione sanguigna
- Spessore della pelle
- Insulina
- BMI
- Pedigree del diabete
- Età
- Diagnosi di diabete (0 = no, 1 = sì)

## ⚙️ Dipendenze

Per eseguire i notebook, assicurati di avere installato:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn qiskit
```

## 🚀 Esecuzione

1. **Preprocessing**: Avvia `Dataset_Preprocessing.ipynb` per analizzare e preparare i dati.
2. **Classificazione Classica**: Esegui `ML_classification.ipynb` per testare diversi modelli ML.
3. **Classificazione Quantistica**: Esegui `VQC.ipynb` per testare un modello VQC tramite Qiskit.

## 📈 Risultati

Nel progetto vengono confrontate:

- Accuratezze e metriche dei modelli classici
- Performance del modello quantistico su dati con un numero di feature variabili (3 ,4 e 5)


## 🔬 Tecnologie Utilizzate

- **Python 3.x**
- **Scikit-learn**
- **Qiskit**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Jupyter Notebook**

## 📚 Riferimenti

- [UCI ML Repository – Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- [Qiskit Documentation](https://qiskit.org/documentation/)

## 👤 Autore

Progetto realizzato da *Rocco Pio Vardaro* e *Antonio Pio Francica* nel contesto di studio/sperimentazione sulle tecnologie classiche e quantistiche applicate alla medicina predittiva.
