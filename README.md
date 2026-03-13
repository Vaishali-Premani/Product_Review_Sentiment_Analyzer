# Product Review Sentiment Analyzer

A Machine Learning and Natural Language Processing (NLP) based web application that analyzes customer product reviews and classifies them as **Positive** or **Negative**.  
The project uses Amazon Alexa product reviews and deploys a trained ML model through a **Flask web application** to perform real-time sentiment analysis for both **single review input** and **bulk review prediction via CSV file**.

---

## 📌 Project Overview

In the digital era, customers frequently express their opinions about products through online reviews. These reviews contain valuable insights that can help businesses understand customer satisfaction and improve their products.

However, manually analyzing a large number of reviews is time-consuming and inefficient. This project solves the problem by building an **automated sentiment analysis system** using **Machine Learning and NLP techniques**.

The system processes textual reviews, converts them into numerical features, and predicts whether the sentiment of the review is **positive or negative**. A **Flask-based web application** allows users to interact with the model easily.

---

## 🌟 Features

- Sentiment classification of product reviews
- Single review prediction
- Bulk prediction using CSV file upload
- Sentiment distribution visualization
- Machine learning model comparison
- User-friendly web interface using Flask
- Real-time prediction

---

## 🧠 Tech Stack

**Programming Language**

- Python

**Machine Learning & NLP**

- Scikit-learn
- XGBoost
- NLTK

**Data Processing**

- Pandas
- NumPy

**Visualization**

- Matplotlib

**Web Development**

- Flask
- HTML / CSS (Frontend)

---

## 📊 Dataset

The project uses **Amazon Alexa product reviews dataset**, which contains customer feedback about Alexa-enabled products.

Dataset includes:

- Customer review text
- Sentiment label
- Product-related information

The reviews are used to train machine learning models to classify sentiments.

---

## Machine Learning Models Used

The following models were implemented and compared:

- Decision Tree
- Random Forest
- XGBoost

After evaluation, **XGBoost** performed the best and was selected for deployment.

---

## Data Preprocessing

Before training the model, the dataset undergoes several preprocessing steps:

1. Removing special characters
2. Converting text to lowercase
3. Tokenization
4. Stopword removal
5. Stemming using Porter Stemmer
6. Text vectorization using **CountVectorizer (Bag of Words)**

These steps help convert raw textual data into numerical features suitable for machine learning models.

---

## 🔄️ System Workflow
Dataset
   ↓
Data Preprocessing
   ↓
Text Vectorization (CountVectorizer)
   ↓
Machine Learning Model Training
   ↓
Model Evaluation & Selection
   ↓
Model Deployment using Flask
   ↓
User Input (Review / CSV File)
   ↓
Sentiment Prediction
   ↓
Result Visualization