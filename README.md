# Email Classification-Model

## Overview

The Spam Mail Prediction Model project aims to classify emails as either spam or not spam. It utilizes the TF-IDF vectorizer for text processing to transform the email data into numerical features. The model then applies machine learning techniques to make accurate predictions based on patterns within the data.

## Technologies Used

- Python
- scikit-learn
- pandas
- pickle

## Algorithms Used

- Logistic Regression
- Decision Tree Classifier

## Dataset

The model is trained on a dataset of labeled emails, consisting of spam and not spam categories. You can find various open-source email datasets online, such as [Kaggle's Spam Email Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## How It Works

Data Preprocessing: The input email text is cleaned and processed.

TF-IDF Vectorization: The processed text is converted into numerical vectors using the TF-IDF vectorizer.

Prediction: The vectorized data is fed into the trained logistic regression model to classify the email as spam or not spam.

## Results

The model achieved an accuracy of 96.68% on the test dataset. The performance can be further improved with additional training data and enhancements.






Bibhash Dash.
