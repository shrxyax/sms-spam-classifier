# sms-spam-classifier
This project is an SMS Spam Classifier built using Python and machine learning. It uses a trained model to classify messages as **spam** or **not spam (ham)** based on their content.

## Features

- Preprocessing of text (tokenization, removing stopwords, etc.)
- Feature extraction using TF-IDF
- Machine learning model training and evaluation
- Web interface using Streamlit
- Interactive prediction for user input

  ## Model Details

- **Vectorizer**: `TfidfVectorizer`
- **Model**: `Multinomial Naive Bayes` 
- Trained on a dataset of SMS messages labeled as spam/ham

## How it works
Takes user input (SMS text)
Preprocesses the text (tokenization, cleaning, etc.)
Transforms the text using the trained TF-IDF vectorizer
Predicts using the trained ML model
Displays whether the SMS is spam or ham

## Dataset
You can use the SMS Spam Collection Dataset from UCI/Kaggle.

## Built With
Python
Pandas, Scikit-learn, NLTK
Streamlit
Jupyter Notebook / PyCharm
