# 📩 SMS Spam Detection

## 📌 Project Overview

This project focuses on detecting spam SMS messages using Machine Learning and Natural Language Processing (NLP).

The goal is to automatically classify text messages as:

- Spam
- Ham (Legitimate Message)

The model learns patterns from message content and predicts whether a message is unwanted spam or a normal message.

---

## 📊 Dataset Description

The dataset contains labeled SMS messages categorized into:

- Ham (Legitimate Messages)
- Spam Messages

The text data is preprocessed and transformed into numerical features using TF-IDF Vectorization before training machine learning models.

---

## ⚙️ Workflow

### 1. Data Cleaning
- Removed unnecessary columns
- Renamed features
- Removed duplicate records
- Encoded target labels

### 2. Exploratory Data Analysis (EDA)
- Target distribution analysis
- Message length analysis
- Correlation analysis
- Data visualization using Matplotlib and Seaborn

### 3. Feature Engineering
Created additional text-based features:
- Character Count
- Word Count
- Sentence Count

### 4. Text Preprocessing
- Lowercasing
- URL removal
- Number removal
- Tokenization
- Stopword removal
- Lemmatization
- Punctuation removal

### 5. Feature Extraction
- TF-IDF Vectorization (3000 Features)

### 6. Model Training
- Train/Test Split (80/20)
- Multiple machine learning models were evaluated

---

## 🤖 Models Used

- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Logistic Regression
- Linear Support Vector Classifier (LinearSVC)

---

## 📈 Evaluation Metrics

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Classification Report
- Confusion Matrix

---

## 🏆 Results

### Best Model: LinearSVC

The Linear Support Vector Classifier achieved the best overall performance for SMS spam detection after comparing multiple machine learning algorithms.

---

## 💾 Model Deployment Preparation

The trained model and TF-IDF vectorizer were saved using Pickle:

- spam_model.pkl
- tfidf_vectorizer.pkl

This allows the model to be reused in web applications and production environments.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Pickle

---

## 👤 Author

Mohamed Hazem

AI Engineer | Machine Learning & NLP Enthusiast
