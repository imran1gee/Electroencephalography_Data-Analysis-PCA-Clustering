# Electroencephalography-EEG-PCA-Hierarchical-Clustering

This repository showcases a project focused on analyzing EEG (Electroencephalography) data using **Principal Component Analysis (PCA)** for dimensionality reduction followed by **Hierarchical Clustering**. The goal of this project is to explore the brain activity patterns captured in the EEG data, reduce the dimensionality of the features, and apply clustering techniques to identify distinct patterns or states of brain activity.

## Table of Contents
1. [Project Overview](#project-overview)
2. [EEG Dataset Description](#eeg-dataset-description)
3. [Dimensionality Reduction using PCA](#dimensionality-reduction-using-pca)
4. [Clustering using Hierarchical Clustering](#clustering-using-hierarchical-clustering)
5. [Results & Interpretation](#results--interpretation)
6. [Conclusions](#conclusions)
7. [Dependencies](#dependencies)

## Project Overview

This project leverages **EEG data** to analyze and classify brain activity patterns. It combines **Principal Component Analysis (PCA)** for reducing the complexity of high-dimensional EEG data and **Hierarchical Clustering** to identify natural groupings of the data. The main steps involved in this project are:

- **Loading and understanding EEG data**: The data is sourced from the EEG dataset on Kaggle.
- **Applying PCA**: We perform dimensionality reduction to simplify the dataset while preserving the most important features of brain activity.
- **Clustering with Hierarchical Clustering**: The reduced data is clustered to identify distinct brain activity states.
- **Visualization**: The results are visualized using dendrograms and scatter plots to understand the clustering results.

## EEG Dataset Description

The dataset used in this project is the **EEG Dataset** from Kaggle. It contains data recorded from EEG sensors, capturing brain activity in various states. The dataset includes:

- **EEG_data**: Time-series features representing electrical brain activity recorded across multiple EEG channels.
- **Target**: Labels indicating different brain activity states, such as relaxed, focused, or other cognitive states.

You can access the dataset here: [EEG Dataset on Kaggle](https://www.kaggle.com/datasets/samnikolas/eeg-dataset).

The EEG dataset provides valuable insight into how the brain reacts to various stimuli and mental states, making it ideal for the application of clustering techniques.

## Dimensionality Reduction using PCA

**Principal Component Analysis (PCA)** is applied to the EEG dataset to reduce its dimensionality, which simplifies the analysis while retaining the most important aspects of the data. This reduction helps in:

- Reducing computational complexity
- Identifying the most important patterns in the EEG signals
- Enhancing the clustering process by focusing on the most relevant features of the data

By projecting the EEG data into a lower-dimensional space, PCA makes it easier to uncover relationships and structures in the data that were previously hidden in the higher dimensions.

## Clustering using Hierarchical Clustering

**Hierarchical Clustering** is applied to the reduced-dimension EEG data to group similar brain activity patterns. This method builds a hierarchy of clusters, which allows us to:

- Identify natural groupings of brain states or mental activities
- Visualize the clustering results using a **dendrogram**, which shows the hierarchical relationships between the different clusters
- Gain insights into the similarity of various brain states

The results of this clustering are visualized through scatter plots and dendrograms, providing a clear picture of how different brain activity patterns are grouped together.

## Results & Interpretation

The results section showcases visualizations that highlight the effectiveness of PCA and Hierarchical Clustering in analyzing EEG data:

- **PCA transformation**: The data after applying PCA is visualized, showing the reduced dimensions and the key patterns in the EEG signals.
- **Clustering**: The dendrogram illustrates how the EEG data clusters into distinct brain activity states. Scatter plots help to visualize the relationships between the clustered data points.

Through these visualizations, we can interpret the effectiveness of the dimensionality reduction and clustering techniques, providing insights into the structure of brain activity.

## Conclusions

The project demonstrates how **PCA** and **Hierarchical Clustering** can be used together to analyze **EEG data**, reducing dimensionality and uncovering natural groupings of brain activity states. The key findings include:

- The successful reduction of dimensionality while retaining important EEG features.
- Clear clustering of different brain activity states, which could be useful for various cognitive state classification tasks or neurological studies.

This project highlights the power of **PCA** and **Hierarchical Clustering** in simplifying and analyzing complex brain activity data.

## Dependencies

The following Python libraries are required for this project:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
