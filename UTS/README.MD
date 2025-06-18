# UTS — Disaster Tweet Classification with NLP

This project is part of the UTS (midterm project) for the Natural Language Processing course, based on the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started). It focuses on classifying social media content using classical machine learning and NLP techniques.

## Problem Statement

Sometimes, social media posts contain ambiguous language. For instance, the word **“ablaze”** may be used metaphorically to mean *cheerful* or literally to describe *a fire or explosion*. The task is to detect whether a tweet truly refers to a disaster.

## Dataset

The dataset consists of tweets labeled with:
- **1** → real disaster-related tweet  
- **0** → not about a disaster  

The data is available [here](https://www.kaggle.com/competitions/nlp-getting-started/data).

## Objectives

- Build two machine learning models: **Naive Bayes** and **Logistic Regression**
- Predict whether a tweet refers to a real disaster
- Analyze and interpret model performance
- Use **POS tagging** and **sequence labeling** to identify possible disaster location entities

## Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   Understand data structure, keyword distributions, and class balance

2. **Data Preprocessing**  
   Clean text data: case folding, punctuation removal, tokenization, stopword removal

3. **Text Vectorization**  
   Use TF-IDF or CountVectorizer to convert text into numerical format

4. **Model Training**  
   Train both Naive Bayes and Logistic Regression models for binary classification

5. **Evaluation & Validation**  
   Use metrics like **F1 score**, precision, recall, and confusion matrix

6. **Model Interpretability**  
   Apply **POS tagging** and simple sequence labeling to extract disaster-related location clues from tweets

## Tools & Libraries

- Python (Jupyter Notebook)
- scikit-learn, NLTK, pandas, matplotlib, seaborn
- Google Colab
  
