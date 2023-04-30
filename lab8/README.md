# Lab 8

## Overview

This Notebook demonstrates how to use indexing with graphs to efficiently search for nearest neighbors in a dataset. The notebook uses the Jeopardy dataset, which is downloaded and unpacked. The data is then read as CSV and embedded using the Spacy model. The notebook implements index construction with different index methods and spaces, including 'nsw', 'hnsw', and 'cosinesimil'. The notebook also demonstrates how to compute recall@N, and how to vary parameters of the index to see how it influences construction and search time.

## Dependencies

- spacy
- fasttext
- nmslib
- csv
- numpy
- tqdm
- pickle
- os
- gc
- itertools
- time
- pandas
- matplotlib

## Contents

The notebook contains the following sections:

1. **Index construction**: Here, vectors are generated using the Jeopardy dataset and indexed using different methods and spaces.

2. **Construct buckets with ground truth**: This section creates buckets with ground truth to collect accurate nearest neighbors with a flat index.

3. **Test HNSW**: This section creates an index with default settings and assesses its recall numbers.

4. **Assessment**: This section varies the parameters of the index to see how they influence the construction time, search time, and recall numbers for different values of `D`, `M`, and `ef`.

5. **Displaying results**: The results of the previous sections are displayed and discussed.

## Results

The main results and insights from this notebook include:

- Different index construction methods and spaces affect the performance of the index, including construction time, search time, and recall numbers.
- Increasing the value of `ef` and `M` generally improves the quality of the constructed graph and leads to higher accuracy of search but also leads to longer indexing times.
- The recall numbers generally improve with increasing values of `D`, `M`, and `ef`.

## Usage

To run this notebook, make sure that all the required dependencies are installed. Then, simply open the IPython Notebook file "Indexing with graphs.ipynb" and follow the instructions in each section.
