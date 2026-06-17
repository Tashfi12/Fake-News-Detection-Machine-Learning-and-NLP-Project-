# Fake-News-Detection-Machine-Learning-and-NLP-Project-
Fake News Detection using NLP and Machine Learning. This project applies text preprocessing, TF-IDF vectorization, and machine learning algorithms including Multinomial Naive Bayes, Logistic Regression, and Passive Aggressive Classifier to classify news articles as Fake or Real.

# Fake News Detection using Machine Learning and NLP

This project implements a Fake News Detection system using Natural Language Processing (NLP) and Machine Learning techniques to classify news articles as either **Fake** or **Real**.

## Project Overview

The objective of this project is to automatically identify misleading or fake news articles by analyzing textual content. The project follows a complete NLP pipeline including data preprocessing, feature extraction, model training, and performance evaluation.

## Features

- Text Cleaning using Regular Expressions
- Stopword Removal
- Word Stemming using Porter Stemmer
- TF-IDF Vectorization with Uni-gram, Bi-gram, and Tri-gram features
- Training and Evaluation of Multiple Machine Learning Models
- Confusion Matrix Visualization
- Manual Testing for Custom News Articles

## Machine Learning Models

The following classification algorithms were implemented and compared:

- Multinomial Naive Bayes
- Logistic Regression
- Passive Aggressive Classifier

## Technologies Used

- Python
- Pandas & NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Matplotlib & Seaborn
- Google Colab

## Workflow

1. Load and clean the dataset
2. Remove missing values
3. Preprocess text:
   - Convert to lowercase
   - Remove special characters and stopwords
   - Apply Porter Stemming
4. Convert text into numerical features using TF-IDF Vectorizer
5. Split data into training and testing sets
6. Train multiple machine learning models
7. Evaluate models using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
8. Test the model with custom news articles

## Goal

The goal of this project is to demonstrate how Natural Language Processing and Machine Learning can be combined to build an effective fake news detection system that helps identify misinformation automatically.
