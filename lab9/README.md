# Lab 9

## Overview

This Jupyter notebook explores how trees can be utilized for indexing of vector data. The notebook generates and plots a dataset of 30K 2D points that are uniformly distributed in a 1x1 square. The notebook then builds four tree indices, namely KDTree, BallTree, VPTree, and Annoy, and compares their performance in terms of time and recall. In addition, the notebook performs scalability testing by varying the `D` parameter that corresponds to the data dimensionality. Finally, the notebook provides an analysis of the graphs and discusses the choice of data structure for various tasks.

## Dependencies

The notebook requires the following packages or libraries:

- scikit-learn (sklearn)
- matplotlib
- numpy
- annoy
- vptree
- pandas

## Contents

This notebook contains the following sections:

- Get a dataset
- Build four tree indices: KDTree, BallTree, VPTree, and Annoy
- Prepare ground truth and formula for Recall@N
- Assess the performance of each index
- Scalability testing
- Graph analysis

## Results

The notebook provides performance comparisons and scalability testing for four tree indices, namely KDTree, BallTree, VPTree, and Annoy. The results show that Annoy with 100 trees performs the best, followed by BallTree and KDTree. VPTree was found to be too slow and was eliminated from the contest. The notebook also provides an analysis of the graphs and discusses the choice of data structure for various tasks.

## Usage

To run the notebook, open the file "Indexing with trees.ipynb" in a Jupyter notebook environment and run each cell.
