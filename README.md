# -Event-Detection-in-Social-Media-Streams

## Overview
This project focuses on event detection from text data using Natural Language Processing (NLP) techniques and clustering methods. The primary goal is to extract meaningful clusters from a dataset of comments and identify potential events based on keyword detection. The clustering is performed using the K-Means algorithm, and visualization techniques such as word clouds and PCA are used to analyze the results.

## Features

- Data Preprocessing:

- Converts text to lowercase

- Removes URLs and special characters

- Tokenization

- Stopword removal

## Text Vectorization:
- Uses TF-IDF to convert text data into numerical form

## Clustering: 
- Implements K-Means clustering

## Visualization:

- Word clouds for each cluster

- PCA for dimensionality reduction

## Event Detection: Identifies potential events using predefined keywords

## Evaluation Metrics:

- Silhouette Score

- Davies-Bouldin Index

- Elbow Method for optimal cluster selection

## Dataset
The project uses a dataset containing user comments. The dataset should be in CSV format with a column named comment_text.

