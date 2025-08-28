# stylesense-reco-pipeline

# dsnd-pipelines-project

This repository contains starter code for the Udacity Data Scientist Nanodegree Capstone Project, focused on building a machine learning pipeline for product recommendations based on customer reviews.

## Project Scenario

You’ve joined StyleSense, a fast-growing women’s fashion e-retailer. Reviews often miss the “recommend/not recommend” label, but still contain useful text and metadata. Your job is to use reviews with complete labels to train a model that predicts whether a customer would recommend a product, then apply it to fill in the missing ones. This helps track satisfaction and trending products.

## What you must build

A machine-learning pipeline that ingests:

*   Text (review body),
*   Numerical features (e.g., age, rating),
*   Categorical features (e.g., product category).

Proper preprocessing for each type (impute/scale numeric, encode categoricals, tokenize/TF-IDF text).

Feature engineering from text (e.g., n-grams/TF-IDF).

A combined end-to-end pipeline (preprocess → features → model).

Hyperparameter tuning to find optimal settings.

Evaluation on a held-out test set; then train on full training data and use the model to predict missing labels.

## Task checklist

1.  Create preprocessing for numeric, categorical, and text data.
2.  Create text processing steps (e.g., TF-IDF with n-grams).
3.  Build text features to feed the model.
4.  Combine everything in a single scikit-learn Pipeline.
5.  Fine-tune with cross-validation.
6.  Evaluate the final pipeline on test data.

## Environment (Python)

*   scikit-learn
*   numpy
*   pandas
*   spacy (for NLP if needed)

## Setup
