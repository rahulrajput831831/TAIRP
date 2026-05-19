# Twitter Sentiment Analysis using NLP, VADER, and RoBERTa

## Project Overview

This project analyzes public sentiment on demonetization-related tweets using Natural Language Processing (NLP).

Two sentiment analysis approaches were implemented:

- VADER (Rule-Based Sentiment Analysis)
- RoBERTa (Transformer-Based Sentiment Analysis)

The project includes:
- tweet preprocessing
- exploratory data analysis
- sentiment classification
- comparative analysis
- visualizations

---

## Project Structure

Twitter-Sentiment-Analysis/

├── data/

├── notebooks/

│ ├── 01_data_cleaning.ipynb

│ ├── 02_eda.ipynb

│ ├── 03_vader_analysis.ipynb

│ ├── 04_roberta_analysis.ipynb

│ └── 05_model_comparison.ipynb

├── outputs/

├── requirements.txt

├── README.md

└── .gitignore

---

## Workflow

### 1 Data Cleaning
- Remove URLs
- Remove mentions
- Remove hashtags
- Tokenization
- Stopword Removal
- Lemmatization

### 2 Exploratory Data Analysis
- Tweet Length Analysis
- Word Frequency
- Word Cloud

### 3 VADER Sentiment Analysis
- Compound Score
- Sentiment Classification

### 4 RoBERTa Sentiment Analysis
- Transformer Prediction
- Batch Processing

### 5 Model Comparison
- Visualization
- Performance Comparison

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Transformers
- PyTorch

---

## Results

RoBERTa demonstrated stronger contextual sentiment understanding.

VADER showed faster execution.

---

## Conclusion

RoBERTa achieved superior contextual understanding while VADER provided lightweight sentiment prediction.