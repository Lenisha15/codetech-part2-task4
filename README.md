Name: LENISHA ROSHAL DSOUZA

Company: CODTECH IT SOLUTIONS

ID: CT08DGD

Domain: Python Programming

Duration: Dec 20,2024 to Jan 20,2025

Overview of the Spam Email Classification Model

This script demonstrates the process of building a spam email classification model using a machine learning approach. The goal is to classify emails as either spam or not spam based on their text content. Here's a breakdown of the steps:

Data Loading: The dataset, which contains email text and corresponding labels (spam or not spam), is loaded into a pandas DataFrame from a CSV file.

Data Preprocessing:

The email text (features) is extracted from the dataset, and the labels (target) are also separated.
The data is split into training and testing sets, with 80% used for training and 20% for testing.
Text Vectorization:

The CountVectorizer from scikit-learn is used to convert the raw email text into a matrix of token counts (bag-of-words model). This is necessary for machine learning models to process text data.
Model Training:

A Naive Bayes classifier (MultinomialNB) is chosen for training. This model is well-suited for text classification tasks, especially when dealing with word frequency counts.
The model is trained on the vectorized training data.
Prediction:

The trained model is used to predict the labels for the test set.
Evaluation:

The accuracy of the model is computed by comparing the predicted labels with the actual labels from the test set.
A classification report is generated, providing additional metrics such as precision, recall, and F1-score for both classes (spam and not spam).
Expected Output:
Accuracy: The percentage of correctly classified emails in the test set.
Classification Report: A detailed performance report showing the precision, recall, and F1-score for each class (spam and not spam).
