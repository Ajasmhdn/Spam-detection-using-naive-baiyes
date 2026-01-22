# Spam Detection Using Naive Bayes

A simple and effective **Spam Message / Email Detection system** built using **Naive Bayes classification** and basic **Natural Language Processing (NLP)** techniques.  
This project classifies text as **Spam** or **Ham (Not Spam)** using supervised machine learning.

---

## 📌 Project Overview

Spam detection is a common real-world NLP application. In this project, we:
- Clean and preprocess message text
- Convert text into numeric features (Bag of Words / TF-IDF)
- Train a **Naive Bayes model**
- Predict whether a given message is **Spam** or **Ham**

---

## 🚀 Features

✅ Text preprocessing (lowercase, punctuation removal, stopword removal)  
✅ Feature extraction using **TF-IDF / CountVectorizer**  
✅ Model training with **Multinomial Naive Bayes**  
✅ Accuracy and evaluation metrics (confusion matrix, classification report)  
✅ Custom prediction for user input messages  

---

## 🧠 Machine Learning Model

- **Algorithm:** Naive Bayes (MultinomialNB)
- **Category:** Supervised Learning (Text Classification)
- **Input:** Message text
- **Output:** Spam / Ham

---

## 🗂 Dataset

The dataset contains labeled text messages:
- `spam` → unwanted/promotional messages
- `ham` → normal genuine messages

Example format:

| label | message |
|------|---------|
| ham  | Hey, are we meeting today? |
| spam | Congratulations! You won a free prize... |

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install -r requirements.txt
