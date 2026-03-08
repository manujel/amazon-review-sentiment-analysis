# Amazon Review Sentiment Analysis

This project implements a sentiment analysis system for Amazon product reviews using Natural Language Processing (NLP) and machine learning.

The goal is to predict the numerical rating (1–5 stars) of a product review based on its textual content.

## Dataset

The dataset is based on the publicly available **Amazon Reviews 2023 dataset**.

Four product categories were selected:

- CDs and Vinyl
- Digital Music
- Handmade Products
- Video Games

A total of **20,000 reviews** were used (5,000 per category).

## Methodology

The following steps were performed:

1. Data preprocessing and cleaning
2. Combining review title and text
3. Feature extraction using **TF-IDF**
4. Training classification models

Two machine learning models were evaluated:

- Logistic Regression
- Multinomial Naive Bayes

## Results

| Model | Accuracy |
|------|------|
Logistic Regression | 0.7645 |
Naive Bayes | 0.7313 |

The Logistic Regression model achieved the best performance.

## Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud

## Author

Manujel Prlic  
IU International University of Applied Sciences  
B.Sc. Applied Artificial Intelligence