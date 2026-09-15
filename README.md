# 🐦 Twitter Sentiment Analysis

A machine learning project that classifies tweets as **Positive** or **Negative** using Natural Language Processing and Multinomial Naive Bayes.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)

---

## 📌 Project Overview

This project performs **Sentiment Analysis** on Twitter data. The model predicts whether a given tweet expresses a positive or negative sentiment.

**Dataset**: Twitter Sentiment dataset containing Topic, Sentiment, Tweet ID, Date, and Tweet Text.

---

## 🛠️ Approach

1. Data Loading & Exploration
2. Text Cleaning (lowercase + remove punctuation)
3. Text Vectorization using `CountVectorizer`
4. Model Training – Multinomial Naive Bayes
5. Evaluation & Prediction on new tweets

---

## 📊 Sample Predictions

| Tweet | Prediction | Confidence |
|-------|------------|------------|
| I absolutely love this new phone! The camera is amazing... | Positive | 99.37% |
| This is the worst service I have ever experienced... | Negative | 85.41% |
| Wow! What a fantastic performance by the team today! | Positive | 96.84% |
| The product broke after two days. Total waste of money. | Negative | 89.31% |

---

## 🚀 How to Run

1. Clone the repository
2. Place `twitter_sentiment.csv` in the same folder
3. Open the notebook in Jupyter or Google Colab
4. Run all cells

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
