# Lab 7

Vector space with ML: The use of ML model for the needs of information retrieval and text classification.

## Purpose of the notebook

The goal of this lab is to show how to retrieve relevant information from a given dataset. The facts dataset is provided, and the idea is to retrieve facts relevant to the query. For example, typing "good mood" should return a fact like "Cherophobia is the fear of fun". To accomplish this, the notebook shows how to use document vectors obtained using machine learning models instead of the traditional tf-idf and dimension reduction methods.

## Main results and insights

The main results and insights from the notebook include:

- Using neural networks to embed sentences
- Writing a function that prepares embedding of arbitrary queries
- Transforming sentences to vectors
- Finding the closest facts to a given query using cosine similarity
- Measuring DCG@5 for a given set of queries

## Dependencies

The notebook requires the following packages or libraries:

- `tensorflow_hub`
- `numpy`
- `requests`

## Contents

The notebook consists of the following sections:

1. Use neural networks to embed sentences
2. Write a function that prepares embedding of arbitrary queries
3. Read the data
4. Transform sentences to vectors
5. Find closest to the query
6. Measure DCG@5 for the following query bucket
