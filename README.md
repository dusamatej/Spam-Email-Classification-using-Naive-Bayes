# Spam-Email-Classification-using-Naive-Bayes

Authors: Ondrej Dusa (https://ondrej-dusa.github.io/Portfolio/), Matej Dusa

This project implements a spam email classification model using Natural Language Processing (NLP) techniques and Multinomial Naïve Bayes. The dataset contains labeled emails, which are preprocessed and vectorized before being classified as spam or not spam.

Project Overview
Preprocessing Steps:
Convert text to lowercase.
Remove special characters using regex.
Tokenize text by splitting words.
Remove stopwords (common words like "the", "is", etc.).
Apply stemming using PorterStemmer to reduce words to their root form.
Feature Extraction:
Use CountVectorizer to convert text into a numerical matrix for model training.

Model Selection:
Implement Multinomial Naïve Bayes (MultinomialNB) for classification.
Evaluation Metrics:
Generate a classification report with precision, recall, F1-score, and accuracy.
Results
The classification report indicates:

Accuracy: 50%
Imbalanced Dataset: The model struggles with recall for class 0 (non-spam), suggesting a small dataset size.

Files in the Repository
spam_classifier.ipynb – Jupyter Notebook containing the full implementation.
emails.csv – Sample dataset
README.md – Project documentation.
