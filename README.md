# IMDB Sentiment Analysis using Word2Vec

## Project Overview

This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing (NLP).

The reviews are preprocessed and tokenized before training a Word2Vec model. Each review is then converted into a fixed-length numerical vector using the average of its word embeddings. Machine learning classification models are used to predict whether a movie review is positive or negative.

## Dataset

The dataset contains IMDB movie reviews with two columns:

- review - Movie review text
- sentiment - Positive or negative sentiment

## Technologies Used

- Python
- Pandas
- NumPy
- Regular Expressions
- Gensim
- Word2Vec
- Scikit-learn
- Jupyter Notebook

## Project Workflow

text
IMDB Reviews
     ↓
Text Cleaning
     ↓
Tokenization
     ↓
Word2Vec Training
     ↓
100-Dimensional Word Embeddings
     ↓
Average Word2Vec
     ↓
Train/Test Split
     ↓
Machine Learning Classification
     ↓
Sentiment Prediction
     ↓
Model Evaluation
