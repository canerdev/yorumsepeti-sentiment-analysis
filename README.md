# Turkish Restaurant Review Sentiment Analysis

A machine learning project that performs sentiment analysis on Turkish restaurant reviews using Naive Bayes classification.

## Overview

This project analyzes restaurant reviews from a Turkish food delivery platform, Yemek Sepeti, classifying customer sentiments as positive or negative based on their reviews and ratings. The system uses natural language processing techniques specifically adapted for the Turkish language.

## Features

- Processing of multi-dimensional restaurant ratings (speed, service, flavor)
- Text preprocessing pipeline for Turkish language:
  - Case normalization
  - Tokenization
  - Stopword removal
  - Turkish stemming
- Naive Bayes classification for sentiment analysis
- Training and testing functionality

## Dependencies

- numpy
- pandas
- nltk
- snowballstemmer
- scikit-learn
- trtokenizer

## Dataset

The dataset includes restaurant reviews with the following features:

- Speed rating (1-10)
- Service rating (1-10)
- Flavor rating (1-10)
- Text review

## Usage

The main implementation is provided in `yorumsepeti.ipynb` Jupyter notebook, which contains the complete workflow from data preprocessing to model training and evaluation.

## Implementation Details

1. Data Preprocessing:

   - Converts ratings to binary sentiment labels
   - Cleans and normalizes text data
   - Implements Turkish-specific text processing

2. Model:
   - Uses Naive Bayes classification
   - Includes custom implementation of likelihood calculations
   - Provides prediction functionality for new reviews
