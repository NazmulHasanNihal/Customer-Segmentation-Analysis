# Customer Segmentation Analysis

This project focuses on customer segmentation using clustering techniques on a Walmart dataset. The workflow includes data preprocessing, clustering, dimensionality reduction, visualization, model training, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Code Explanation](#code-explanation)
  - [Data Preprocessing](#data-preprocessing)
  - [Elbow Method for Optimal Clusters](#elbow-method-for-optimal-clusters)
  - [K-Means Clustering](#k-means-clustering)
  - [PCA Visualization](#pca-visualization)
  - [t-SNE Visualization](#tsne-visualization)
  - [Boxplot Visualization](#boxplot-visualization)
  - [MiniBatchKMeans Clustering](#minibatchkmeans-clustering)
  - [DBSCAN Clustering](#dbscan-clustering)
  - [Random Forest Feature Importance](#random-forest-feature-importance)
  - [Correlation Matrix](#correlation-matrix)
  - [Logistic Regression Model Training and Evaluation](#logistic-regression-model-training-and-evaluation)
- [Results](#results)
- [How to Run](#how-to-run)

## Introduction

The goal of this project is to segment customers based on their purchasing behavior and demographics using clustering algorithms. This segmentation helps in identifying distinct customer groups for targeted marketing strategies.

## Dependencies

Ensure you have the following libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- plotly

You can install these libraries using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
