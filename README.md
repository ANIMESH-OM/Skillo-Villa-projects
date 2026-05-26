# Capstone Project: Real-Time Sentiment Analysis on Omicron Variant

## Problem Statement

Perform sentiment analysis on the **Omicron variant** by fetching real-time data directly from Twitter. Sentiment analysis is the process of identifying feelings and emotions expressed in words through Machine Learning or Artificial Intelligence.

**Objective:** Perform sentiment analysis on real-time data collected from Twitter and display the sentiment (Positive/Negative/Neutral).

---

## What is an API?

Imagine you're sitting at a table in a restaurant with a menu. The kitchen is the "system" that prepares your order. The waiter is the messenger that takes your request to the kitchen and delivers your food back.

**That waiter is the API.**

In simple words, an API stands as a **bridge** for one to access the content in another's storage. APIs are huge and used everywhere.

---

## Twitter API - What Can You Extract?

| Feature | Description |
|---------|-------------|
| **Tweets** | Searching, posting, filtering, engagement, streaming |
| **Accounts & Users** | Account management, user interactions |
| **Media** | Uploading and accessing photos, videos, animated GIFs |
| **Trends** | Trending topics in a given location |
| **Geo** | Information about known places or places near a location |

---

## Getting Twitter API Keys

Follow these steps to obtain your API credentials:

1. Login with your normal Twitter credentials
2. Follow the prompts to create a developer project
3. Twitter will provide you with:
   - **API Key** (Consumer Key)
   - **API Secret Key** (Consumer Secret)
   - **Bearer Token**
4. Visit the **Authentication Tokens** area and generate:
   - **Access Token** (Token Key)
   - **Access Token Secret**

> **Important Library:** Tweepy is the library we will use to fetch data from Twitter API.

---

## Project Pipeline

The complete project follows these steps in order:

| Step | Task |
|------|------|
| 1 | Import Necessary Dependencies |
| 2 | Read and Load the Dataset |
| 3 | Exploratory Data Analysis (EDA) |
| 4 | Data Visualization of Target Variables |
| 5 | Data Preprocessing |
| 6 | Split Data into Train and Test Subset |
| 7 | Transform Dataset using TF-IDF Vectorizer |
| 8 | Create Function for Model Evaluation |
| 9 | Model Building |
| 10 | Conclusion |

---

## Code Implementation Import Dependencies
Conclusion
This capstone project successfully demonstrates:

Real-time data fetching from Twitter API using Tweepy

Complete EDA and visualization of Omicron-related tweets

NLP preprocessing pipeline for text cleaning

TF-IDF feature extraction for numerical representation

Multiple ML models (Logistic Regression, Naive Bayes, SVM, Random Forest)

Model evaluation with accuracy, precision, recall, and F1-score

Final sentiment output (Positive/Negative/Neutral) for real-time tweets

The project provides valuable insights into public sentiment regarding the Omicron variant, useful for public health monitoring, brand analysis, and social listening.

Author
Animesh
