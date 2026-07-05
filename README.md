# 📝 Sentiment Analysis using NLP

> A Machine Learning project that classifies Amazon Fine Food Reviews into **Positive**, **Neutral**, and **Negative** sentiments using **TF-IDF** and **Logistic Regression**.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-red)

---
## 📌 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify Amazon Fine Food Reviews into **Positive**, **Neutral**, and **Negative** sentiments.

The project demonstrates the complete NLP workflow, from text preprocessing to model evaluation using Scikit-learn.

---

## 🎯 Objective

The objective of this project is to automatically predict the sentiment of customer reviews using machine learning techniques.

---

## 📂 Dataset

**Amazon Fine Food Reviews Dataset**

- Original Dataset Size: **568,454 reviews**
- Sample Used: **50,000 reviews**

Dataset Source:
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📚 NLP Techniques Used

- Text Cleaning
- Lowercase Conversion
- Punctuation Removal
- Stop Word Removal
- TF-IDF Vectorization

---

## 🤖 Machine Learning Model

**Logistic Regression**

The model was trained on TF-IDF features extracted from customer reviews.

---

## 🔄 Project Workflow

1. Import libraries
2. Load dataset
3. Explore dataset
4. Create sentiment labels
5. Sample 50,000 reviews
6. Clean review text
7. Convert text into TF-IDF vectors
8. Split data into training and testing sets
9. Train Logistic Regression model
10. Evaluate the model
11. Predict sentiment for custom reviews

---

## 📊 Model Evaluation

Evaluation Metrics Used:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Final Accuracy

**85.26%**

---

## 📈 Key Findings

- The model performed well on **Positive** reviews.
- Performance on **Negative** reviews was reasonable.
- **Neutral** reviews were the most difficult to classify due to class imbalance.

---

## 💡 Sample Prediction

**Input Review**

This coffee tastes fantastic. I loved it.

**Predicted Sentiment**

Positive

---

## 📁 Project Files

- `Sentiment_Analysis.ipynb` – Complete Jupyter Notebook
- `sentiment_model.pkl` – Trained Logistic Regression model
- `tfidf_vectorizer.pkl` – Saved TF-IDF vectorizer
- `requirements.txt` – Python dependencies

---

## 🚀 Future Improvements

- Lemmatization
- Hyperparameter Tuning
- Cross Validation
- Word Embeddings (Word2Vec/GloVe)
- BERT-based Sentiment Analysis

---

## 👨‍💻 Author

**Mohammed Amer Ahmed**

- MSc Data Science
- University of Salford
- GitHub: https://github.com/mdamerahmed872-dotcom

---
