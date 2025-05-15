# 📰 Fake News Detection using Machine Learning

Detect whether a news article is **REAL** or **FAKE** using Natural Language Processing (NLP) and Machine Learning.
---

## 🚀 Overview
This project uses **TF-IDF vectorization** and **Logistic Regression** to classify news articles as either **real** or **fake**. It includes:

- Data exploration
- Preprocessing and feature extraction
- Model training and evaluation

---
## 📊 Dataset

- Source: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Contains two files:
  - `Fake.csv`
  - `True.csv`
- Each file has a news title, text, subject, and date

---

## ⚙️ How it Works

1. Load and label real/fake news datasets
2. Preprocess text using:
   - Lowercasing
   - Removing stopwords and punctuation
3. Convert text to numerical format using **TF-IDF**
4. Train **Logistic Regression** model

   ---
## Future Improvements
Train with deep learning (LSTM, BERT)
