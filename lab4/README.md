# Lab 4

## Overview

This Notebook implements a standard document processing pipeline and builds a simple search engine based on it. The notebook contains three main parts:

- Preprocessing: A unified approach to documents and queries preprocessing is implemented using the NLTK library and BeautifulSoup.
- Crawling and Indexing: A web crawler is built using BFS to crawl the Reuters website, and an inverted index is constructed from the collected documents.
- Answering a Query: Two methods for document retrieval are implemented - Boolean Retrieval and Okapi BM25 Ranking Function - both of which utilize the inverted index.

## Dependencies

The following libraries are required to run the notebook:

- nltk
- requests
- bs4
- urllib.parse
- os
- collections
- queue
- pickle
- math
- time

## Contents

The notebook is divided into three main sections:

1. Preprocessing
2. Crawling and Indexing
3. Answering a Query

## Results

The notebook outputs the following results:

- The inverted index, saved as three dictionaries: `doc_urls`, `index`, and `doc_lengths`
- Index statistics, including the number of terms and documents in the index, and the average document length
- Document retrieval results for a sample query using both the Boolean Retrieval and Okapi BM25 Ranking Function methods

## Usage

To run the notebook, open it in Jupyter or another IPython environment and execute the cells in order. The notebook includes detailed comments and explanations for each step of the pipeline, as well as test cases to ensure correct implementation.

Note that the crawling and indexing section may take a significant amount of time to run, especially for larger values of the `depth` parameter in the `crawl_generator_for_index` method. To speed up the process, the crawler only considers pages with content type `html` and ignores other file types such as `.pdf` and `.mp4`.

When running the notebook, make sure all required packages and libraries are installed and imported before starting.
