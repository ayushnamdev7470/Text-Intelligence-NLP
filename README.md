# 🧠 Text Intelligence — NLP Pipelines

> Two end-to-end NLP pipelines built from scratch on 100,000 records

## 📊 Results

| Pipeline | Model | Accuracy | F1 Score |
|----------|-------|----------|----------|
| IMDb Sentiment (50K reviews) | Logistic Regression | 88.8% | 88% |
| News Classification (50K headlines) | Logistic Regression | 65.8% | 66% |

## 🔍 Overview

### Part A — IMDb Sentiment Analysis
- Binary classification: Positive / Negative reviews
- 50,000 IMDb movie reviews
- Logistic Regression outperformed SVM (88.3%), Naive Bayes (85.5%), Random Forest (84.6%)

### Part B — News Classification
- 10-category classification across 50,000 news headlines
- Style & Beauty achieved highest F1: 0.71
- Lower accuracy due to semantic overlap between similar categories

## ⚙️ Pipeline Steps
- Tokenization → Stopword Removal → Lemmatization
- TF-IDF Vectorization (top 5,000 features)
- Model comparison: Logistic Regression, SVM, Naive Bayes, Random Forest

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-9C27B0?style=flat-square)

## 📁 Files
| File | Description |
|------|-------------|
| `NLP Project Part A.ipynb` | IMDb sentiment analysis — preprocessing, TF-IDF, model comparison |
| `NLP Project Part B.ipynb` | News classification — 10 categories, model evaluation |
