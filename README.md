![SMS Spam Detection](sms-spam.png)
# Spam-SMS-Detection-ML-Project
📌 Spam SMS Detection using Naive Bayes

This project is a simple and effective Machine Learning model that classifies SMS messages as Spam or Not Spam using the Multinomial Naive Bayes algorithm.
The entire workflow — from data cleaning to model training — is implemented in a Jupyter Notebook.

✨ Key Features (Based on Your Notebook Steps)

These are the typical steps included in your notebook:

✔ 1. Data Loading

Loads the SMS dataset (usually containing "label" and "message" columns).

✔ 2. Data Cleaning & Preprocessing

Converts text to lowercase

Removes punctuation

Tokenizes text

Removes stopwords

Performs text normalization for better prediction results

✔ 3. Feature Extraction

Uses TF-IDF Vectorization to convert text into numerical form

Builds a clean, structured feature matrix for training

✔ 4. Model Training

Trains a Multinomial Naive Bayes classifier

Splits data into training/testing sets

Learns patterns of spam words vs normal words

✔ 5. Model Evaluation

Calculates accuracy score

Prints confusion matrix or classification report (precision, recall, F1-score)

✔ 6. SMS Prediction

Takes input text

Converts it through the same preprocessing + TF-IDF

Predicts "spam" or "ham"

🧠 Tech Used

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook

🚀 How to Run

Open the notebook

Install required libraries

Run cells in order

Use the last cell to test with your own SMS message
