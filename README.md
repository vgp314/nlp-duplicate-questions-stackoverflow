# nlp-duplicate-questions-stackoverflow

## Problem 
- Using word embedding  to find duplicate questions from [StackOverflow](https://stackoverflow.com).
- Week 3 course of Natural Language Processing course from Coursera.


To solve the problem, you will use two different models of embeddings:

- Pre-trained word vectors from Google which were trained on a part of Google News dataset (about 100 billion words). The model contains 300-dimensional vectors for 3 million words and phrases. GoogleNews-vectors-negative300.bin.gz will be downloaded in download_week3_resources().
- Representations using StarSpace on StackOverflow data sample. You will need to train them from scratch.

## Libraries
In this task you will you will need the following libraries:

StarSpace — a general-purpose model for efficient learning of entity embeddings from Facebook
Gensim — a tool for solving various NLP-related tasks (topic modeling, text representation, ...)
Numpy — a package for scientific computing.
scikit-learn — a tool for data mining and data analysis.
Nltk — a platform to work with human language data.

## Data

- Questions from [StackOverflow](https://stackoverflow.com) provided by Coursera
- Pre-trained word vectors from Google which were trained on a part of Google News dataset (about 100 billion words) [GoogleNews-vectors-negative300.bin.gz]

