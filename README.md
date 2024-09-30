# Fake-News-Prediction-using-RandomForest-
This project implements a machine learning model to classify news articles as "Fake" or "Real" using the Random Forest algorithm. 

The dataset contains various labeled news articles with features like titles, authors, and full text, which are processed to predict whether the news is fake or real.

Features:
Data Preprocessing: The raw news articles undergo cleaning, tokenization, and vectorization (using TF-IDF) to make the text data usable for model training.

Model: Random Forest is employed as the classification model due to its ability to handle large feature sets and provide high accuracy.

Evaluation Metrics: The model's performance is evaluated using accuracy, precision, recall, and F1-score.

Key Steps:

Import Libraries: Utilizes libraries such as pandas, numpy, scikit-learn, and nltk for data manipulation, vectorization, and machine learning.

Data Loading: Reads the dataset (train.csv) containing news articles with labels (1 for fake, 0 for real).

Preprocessing: Includes text cleaning (removal of stopwords, stemming, etc.), and transforming the text using TF-IDF vectorization.

Model Training: Splits the dataset into training and testing sets, then trains the Random Forest model.

Model Evaluation: After training, evaluates the model using metrics such as accuracy to assess its performance.

Requirements:

Python 3.x

Libraries: pandas, numpy, scikit-learn, nltk
