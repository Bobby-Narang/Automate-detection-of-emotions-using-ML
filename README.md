# Emotion Detection from Paragraphs

## About
This project is part of an Internship (TCS iON RIO 210).

## Problem Statement
**RIO-210**: Automate detection of different emotions from paragraphs and predict the overall emotion - (Batch 01).

## Solution
A complete analysis is available [here](emotion-prediction-notebook).

## Contents
- [Libraries](#libraries)
- [Embeddings](#embeddings)
- [Flow](#flow)
- [Model Selection](#model-selection)
- [Result](#result)
- [Data](#data)

## Libraries
**Core Libraries**:
- numpy
- sklearn
- pandas
- matplotlib

**Machine Learning / NLP Libraries**:
- Sci-kit Learn (sklearn)
- NLTK

**Deep Learning Libraries**:
- TensorFlow
- Keras

## Embeddings
FastText pre-trained (English) word vectors were used as embeddings. You can find the vectors [here](https://fasttext.cc/docs/en/english-vectors.html).

## Flow
1. Data Cleaning
2. Data Pre-processing
3. Feature Selection
4. Stopwords Removal
5. Feature Encoding
6. Creating Bag-of-Words (BoW) Model
7. Final Model Creation

## Model Selection
Since the dataset consists of categorical data, classification algorithms were used to strengthen the predictive power of the model.

### Models Built
- Multinomial Naive Bayes
- Random Forest Classifier
- SGD Classifier
- Logistic Regression

## Result
To determine the best model for this classification problem, a comparison was done between all the models.

### Final Result
- **Machine Learning**: SGD Classifier performed slightly better compared to the other models in terms of accuracy.
- **Deep Learning**: The LSTM architecture provided the best results for predicting overall emotion from text, even better than SGD.

## Data
Please refer to the `Data` folder for dataset details.

