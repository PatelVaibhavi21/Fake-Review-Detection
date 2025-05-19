#  Fake Review Detection System

This project is a Python-based system that uses Natural Language Processing (NLP) and Machine Learning to detect fake or deceptive product reviews. It can classify whether a review is genuine or spam based on trained data.

## Features

- Preprocesses text reviews (cleaning, stemming, stopword removal)
- Converts text to numerical features using TF-IDF
- Trains and evaluates a classifier using labeled data
- Predicts if a new review is real or fake
- User input supported via GUI or terminal (if implemented)

##  Dataset

The project uses a dataset (`fake.csv`) that contains two main columns:

- `text`: the review content
- `label`: 1 for **genuine**, 0 for **fake**

You can modify or expand the dataset as needed.

##  How It Works

1. Loads the review dataset
2. Preprocesses the review texts
3. Transforms the text using TF-IDF vectorization
4. Trains a machine learning model (e.g., Logistic Regression)
5. Saves the model and vectorizer for future predictions
6. Accepts new input and classifies the review as fake/genuine
