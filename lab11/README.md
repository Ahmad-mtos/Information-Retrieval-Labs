# Lab 11

## Overview

Implementation of the Shazam algorithm for music identification. The purpose of the notebook is to demonstrate how the algorithm works and provide an understanding of the underlying concepts.

The notebook is based on the paper [An Industrial-Strength Audio Search Algorithm](https://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf) by Avery Li-Chun Wang and collaborators.

## Dependencies

The notebook requires the following packages or libraries:

- ffmpeg
- librosa

You can install ffmpeg using the command `!conda install -c conda-forge ffmpeg -y` and librosa using `!pip install librosa --user`.

## Contents

The notebook covers the following topics:

- Reading and resampling audio tracks database
- Visualizing example spectrogram
- Forming constellations
- Building an index from constellations
- Comparing a query track with the database using index queries
- Implementing a similarity function

## Results

The main insights and results from the notebook include:

- A visualization of the spectrogram of an audio track
- The creation of a database of constellations for each audio track in the database
- The building of an index from the database of constellations
- The identification of matching audio tracks in the database using a query track
- The implementation of a similarity function to estimate the similarity of two audio tracks.

## Usage

To use this notebook, you need to have the required dependencies installed. Once you have installed the dependencies, simply open the notebook in Jupyter and follow the instructions.

## Acknowledgments

This notebook is based on the paper [An Industrial-Strength Audio Search Algorithm](https://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf) by Avery Li-Chun Wang and collaborators. The implementation and code examples in this notebook are based on the original paper and the following libraries:

- librosa
- scipy
- numpy
