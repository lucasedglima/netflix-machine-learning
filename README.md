# Netflix Machine Learning

Collection of machine learning studies developed using the Netflix Titles dataset as part of my Computer Engineering studies at UNIFEI.

The project explores different machine learning concepts through practical analyses, including clustering, classification and dimensionality reduction.

## About the Project

This repository contains three Jupyter Notebook studies using data from Netflix movies and TV shows.

Each notebook focuses on a different machine learning technique:

- K-Means Clustering
- KNN Classification and Confusion Matrix
- Principal Component Analysis (PCA)

The main objective was to apply concepts studied in class to a real dataset and practice the basic steps involved in preparing data, training algorithms and analyzing their results.

## Dataset

The analyses use the `netflix_titles.csv` dataset, which contains information about movies and TV shows available on Netflix.

The dataset includes attributes such as:

- Title
- Content type
- Release year
- Duration
- Genres
- Cast
- Country
- Rating

Different subsets and transformations of these attributes are used depending on the objective of each study.

## Studies

### 1. K-Means Clustering

The `k-means.ipynb` notebook explores unsupervised learning using the K-Means clustering algorithm.

Movies are grouped according to numerical characteristics such as:

- Duration
- Release year
- Number of genres

Before clustering, the selected features are standardized using `StandardScaler`.

PCA is also used to help visualize the resulting clusters in a lower-dimensional space.

### 2. KNN Classification

The `matrizconfusao.ipynb` notebook explores supervised classification using the K-Nearest Neighbors (KNN) algorithm.

The objective is to classify Netflix titles as either **Movie** or **TV Show** using numerical features derived from the dataset.

The study includes:

- Data preparation
- Train/test splitting
- Feature scaling
- KNN classification
- Prediction evaluation
- Confusion matrix analysis

### 3. PCA Dimensionality Reduction

The `reducao.ipynb` notebook explores Principal Component Analysis (PCA).

The analysis uses numerical characteristics such as:

- Duration
- Release year
- Number of genres

After standardizing the features, PCA is applied to reduce the dataset to two principal components, allowing the data to be represented and visualized in a two-dimensional space.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Repository Structure

```text
.
├── k-means.ipynb
├── matrizconfusao.ipynb
├── reducao.ipynb
├── netflix_titles.csv
└── README.md
```

## Concepts Practiced

Through these studies, I practiced concepts including:

- Data preprocessing
- Feature engineering
- Data standardization
- Exploratory data analysis
- Supervised learning
- Unsupervised learning
- K-Means clustering
- KNN classification
- Confusion matrices
- Principal Component Analysis (PCA)
- Dimensionality reduction
- Data visualization

## Academic Context

These studies were developed as part of my Computer Engineering studies at the Federal University of Itajubá (UNIFEI).

The main objective was to apply introductory machine learning and data analysis techniques to a real-world dataset using Python and Scikit-learn.

## Author

**Lucas Eduardo Gomes de Lima**
