# Lab 5

## Overview

This Notebook demonstrates how to implement a spellchecker and a search engine with tolerant retrieval with respect to user queries. The notebook covers two cases:

1. Handling wildcard queries using k-grams
2. Handling typos using different methods such as Norvig's corrector, Soundex, and trigrams with Jaccard coefficient.

The notebook provides a dataset for testing, explores the dataset, and shows how to estimate correction quality.

## Dependencies

The notebook requires the following packages and libraries:

- urllib.request
- nltk
- collections
- re
- jsonlines
- itertools

## Contents

The notebook is divided into the following sections:

1. Handling Wildcards
   - Build Inverted Index of Original Forms
   - Build K-gram Index
   - Generate Wildcard Options
   - Search Wildcard
2. Handling Typos
   - Dataset
   - Implement Context-independent Spellchecker
     - Compute Editorial Distance
     - Norvig's Corrector
     - Soundex
     - Trigrams with Jaccard Coefficient
   - Estimate Quality

## Results

The notebook provides results and insights on how to handle user queries with spelling mistakes or incomplete information.

## Usage

To use the notebook, follow these steps:

1. Install the required dependencies.
2. Load the dataset and explore it.
3. Follow the instructions and implement the different methods for handling wildcards and typos.
4. Test the implemented methods and evaluate the results.
