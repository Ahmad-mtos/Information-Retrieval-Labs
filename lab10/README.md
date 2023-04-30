# Lab 10

## Overview

The Suggest Notebook implements Trie-based index search and generates suggestions for a user query. The notebook uses a dataset of 500 research paper titles to test the Trie-based index search and suggestion functionality. The purpose of this notebook is to provide a non-sensitive and accurate suggestion functionality for user queries.

## Dependencies

The notebook requires the following packages or libraries to run:

- zlib
- base64
- pygtrie
- nltk

To install the necessary dependencies, use the following command:

!pip install --upgrade pygtrie

The notebook also uses the following modules from the nltk package:

- word_tokenize
- stopwords

## Contents

The Suggest Notebook contains the following sections:

1. Data
   - Provides details on the dataset used in the notebook.
2. Trie
   - Implements Trie-based index search to store all texts in lower case.
3. Suggestion Generation
   - Provides a suggest function that generates suggestions for user queries based on the Trie-based index search.
4. Enriching Suggestion Results
   - Proposes a method to enrich suggestion results by identifying phrases in the middle of the text.

## Results

The Suggest Notebook provides a useful tool for generating accurate and non-sensitive suggestions for user queries. With the help of Trie-based index search, the notebook is able to provide quick and efficient search results.

## Usage

To use the Suggest Notebook, open the file in Jupyter Notebook or JupyterLab and run each cell sequentially. To generate suggestions for a user query, call the suggest function and pass in the user query as an argument. The function will return a list of suggested phrases based on the Trie-based index search.
