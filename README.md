
# 📧 Email Spam Detection with Machine Learning

This repository contains a complete machine learning pipeline for detecting spam emails using natural language processing (NLP) and supervised learning techniques.

---

## 📌 Project Overview

The goal of this project is to classify email messages as **Spam** or **Ham** (not spam) using textual content. The notebook walks through:

- Data loading & exploration  
- Text cleaning and preprocessing  
- Feature extraction using **TF-IDF Vectorizer**  
- Model training using **Multinomial Naive Bayes**  
- Model evaluation using metrics like accuracy, precision, recall, and confusion matrix

---

## 📁 Dataset

- **Source**: [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Format: CSV file with two columns:
  - `Category`: Spam or Ham
  - `Message`: Text of the email/SMS

---

## 🛠️ Technologies Used

- **Language**: Python 3
- **Libraries**:
  - `pandas` – data manipulation
  - `numpy` – numerical computing
  - `matplotlib`, `seaborn` – data visualization
  - `sklearn` – machine learning models and metrics
  - `nltk` – text preprocessing (stopwords, stemming)

---

## 🧪 Model Used

- **Multinomial Naive Bayes** – chosen due to its effectiveness in text classification tasks

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
