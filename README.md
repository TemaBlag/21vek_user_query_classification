# Kaggle - 21vek Query Classification Challenge

This repository contains my solutions for the 21vek Query Classification Challenge on Kaggle, organized by 21vek. The task was to classify text queries into multiple categories using various machine learning and natural language processing methods.

📋 Problem Overview
The competition aimed to build a classification system for processing user queries. The queries were to be categorized into multiple classes, including technical questions, product inquiries, general questions, and more. Participants were tasked with using different techniques to build a model that could accurately classify these queries.

⚙️ My Approach
I used several approaches to tackle this problem, combining classical methods and deep learning:

TF-IDF + Logistic Regression: A standard approach using text vectorization and classification with logistic regression.

FastText: A model trained on large data to improve classification accuracy by representing words as dense vectors.

FastText + NN: A combined approach using neural networks for more accurate predictions.

FastText + TF-IDF + CatBoost + Augmentation: A complex model involving multiple algorithms with augmented data to improve results.

Fine-Tuning XLM-RoBERTa: Utilizing pre-trained transformer models for advanced classification.

📈 Results
Each approach yielded different results, and the repository includes a detailed analysis of these outcomes, showing which models performed best under various conditions.

- TF-IDF + Logistic Regression: 84.14%
- FastText: 85.31%
- FastText + NN: 82.02%
- FastText + TF-IDF + CatBoost + Augmentation: 72.74%
- Fine-Tuning XLM-RoBERTa-base: 89.78%
- Fine-Tuning XLM-RoBERTa-large: 86%

📓 Notebook:

* 21vek: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TemaBlag/21vek_user_query_classification/blob/main/21vek.ipynb)


🔗 Links
Kaggle Competition: [21vek Query Classification Challenge](https://www.kaggle.com/competitions/21vek-query-classification/overview)
