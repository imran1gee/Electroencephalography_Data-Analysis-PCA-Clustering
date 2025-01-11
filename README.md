# PCA & Hierarchical Clustering

This repository contains a project that implements Principal Component Analysis (PCA) followed by Hierarchical Clustering to perform dimensionality reduction and clustering. The techniques are applied to explore data patterns and relationships that can help in data analysis and classification tasks.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Dimensionality Reduction using PCA](#dimensionality-reduction-using-pca)
4. [Clustering using Hierarchical Clustering](#clustering-using-hierarchical-clustering)
5. [Results & Interpretation](#results--interpretation)
6. [Conclusions](#conclusions)
7. [Dependencies](#dependencies)

## Project Overview

This project combines Principal Component Analysis (PCA) for dimensionality reduction with Hierarchical Clustering to group data points. The goal is to explore how PCA can be used to reduce the complexity of high-dimensional data, making it easier for clustering algorithms to group similar data points. The project covers:
- Loading and understanding the dataset
- Performing PCA to reduce dimensionality
- Applying Hierarchical Clustering to group data
- Visualizing the results using dendrograms and scatter plots

## Dataset Description

The dataset used in this project includes various features, which could be any high-dimensional data set that needs clustering and dimensionality reduction. The repository includes example data, but you can replace it with your own dataset to try the techniques on different data.

## Dimensionality Reduction using PCA

PCA is applied to reduce the dataset's dimensions, retaining as much variance as possible. This technique helps simplify the analysis of high-dimensional data by projecting it onto a lower-dimensional space.

## Clustering using Hierarchical Clustering

Hierarchical Clustering is used to group similar data points based on the reduced dimensions. The clustering results are visualized using scatter plots and dendrograms to illustrate the grouping hierarchy.

## Results & Interpretation

The results section includes visualizations of the data after PCA transformation and the clustering process. The dendrogram and scatter plots are used to interpret the performance and significance of the clustering, revealing how well the data was grouped after dimensionality reduction.

## Conclusions

This section summarizes the outcomes of applying PCA and Hierarchical Clustering to the dataset, highlighting key findings and their implications. The project demonstrates how these techniques can be used together for effective data analysis.

## Dependencies

The following Python libraries are required for this project:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
