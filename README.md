# Machine Learning Project - Unsupervised Learning

## Project Outcomes

- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four
  main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

### Duration:

Approximately 1 hour and 40 minutes

### Project Description:

In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization
tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a
grocery store.
The project will involve the following tasks:

- Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the
  relationships between the different variables, handle missing values and outliers, and perform feature engineering as
  needed.
- Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering,
  and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine
  the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders
using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

## Project Insights:

Silhouette Score for Clusters:
Make sure to include the silhouette score as part of the clustering analysis. This metric helps evaluate the consistency
within clusters and can guide determining the optimal number of clusters.
Feature Variance Using Components:
After performing dimensionality reduction (e.g., PCA), observe which components explain most of the variance. From the
loading matrix, derive insights about which original features contribute the most to these components.
Readme Revision:
Make the README file more polished and user-friendly. Ensure it explains the objective, tools/libraries used,
methodology, and the insights gained from the analysis. Keep it clean but informative.
Actionable Business Insights:
Provide concise, practical insights that a wholesaler could use, even if they are theoretical. For example:
"Stores that frequently order high quantities of detergents are likely to order substantial amounts of cleaning agents."
"Certain clusters indicate stores with consistent ordering patterns for specific high-margin products, which could be
opportunities for targeted discounts or marketing."

## Overview
This project focuses on applying unsupervised learning techniques to analyze a real-world data set: the "Wholesale Data"
dataset. 

The dataset contains valuable information about various products sold by a grocery store. 

The primary goal of this project is to uncover hidden patterns, group similar data points together, and derive actionable insights that
stakeholders can use to make informed business decisions.

### Methods

1. Exploratory Data Analysis (EDA) and Preprocessing
   Imported and cleaned the dataset, ensuring it is free from missing values and outliers.
2. Visualized relationships between variables using descriptive statistics and plots.
3. Performed feature engineering as required to prepare the data for clustering.
2. Unsupervised Learning Techniques

### KMeans Clustering:

Used to group observations into clusters by minimizing intra-cluster distance.

Determined the optimal number of clusters using metrics like the Silhouette Score.

#### Hierarchical Clustering:

Applied to explore cluster relationships and visualize dendrograms for structure.

#### Principal Component Analysis (PCA):

Performed dimensionality reduction to simplify analysis and focus on the most important features.
Examined variance explained by each PCA component and derived feature significance.

## Results and Insights

### Key Insights:

Clustering Performance:

Clustering achieved with a Silhouette Score of 46, ensuring consistency within clusters.
Cluster 1 contains stores with high detergent orders and low milk orders, targeting a different segment.
Cluster 2 consists of stores with high fresh and frozen orders, indicating a different customer base.

#### Feature Variance & Importance:

2 PCA components explain 72% of total variance.
Features like PC1 and PC2 contribute significantly to the key components.

#### Business Actionable Insights:

Stores with high detergent orders often order substantial cleaning agents, providing an opportunity for bundling
promotions.
Clusters indicate stores with specific ordering patterns of high-margin products, ideal candidates for tailored
marketing campaigns or discounts.

### Visualizations:

Includes scatter plots, dendrograms, or other visuals to support the findings.

### Tools and Libraries

Programming Language: Python 3.13.1
Libraries:

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn