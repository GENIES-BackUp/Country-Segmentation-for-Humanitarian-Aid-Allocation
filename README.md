# Country Segmentation for Humanitarian Aid Allocation

## Overview

This project focuses on the analysis and clustering of countries using socioeconomic and health indicators to support decision-making for an international humanitarian organization.

The objective is to identify groups of countries with similar development profiles and humanitarian needs through unsupervised machine learning techniques.

Two clustering approaches are investigated and compared:

- Hierarchical Agglomerative Clustering (HAC / CAH)
- K-Means Clustering

The resulting country segmentation can help prioritize aid allocation and improve resource distribution strategies.

---

## Problem Statement

International humanitarian organizations often face limited resources and must determine which countries require the most urgent assistance.

By analyzing socioeconomic indicators, countries can be grouped according to their development level, health conditions, and economic situation.

This project aims to provide a data-driven framework for identifying vulnerable countries and supporting humanitarian decision-making.

---

## Objectives

The main objectives of this project are:

- Explore and understand the dataset
- Visualize socioeconomic and health indicators
- Identify patterns and relationships between variables
- Segment countries into homogeneous groups
- Apply Hierarchical Clustering (CAH)
- Apply K-Means Clustering
- Compare clustering results
- Identify countries requiring priority humanitarian intervention

---

## Dataset Description

The dataset contains socioeconomic, demographic, and health indicators for multiple countries.

Examples of variables include:

- GDP per capita
- Child mortality
- Life expectancy
- Health expenditure
- Income level
- Inflation rate
- Fertility rate
- Exports and imports

These indicators provide insights into the economic and social development of each country.

---

## Methodology

### 1. Data Exploration

Initial analysis includes:

- Dataset inspection
- Missing value verification
- Descriptive statistics
- Outlier detection

---

### 2. Data Visualization

Several visualization techniques are used:

- Histograms
- Boxplots
- Correlation heatmaps
- Scatter plots
- Pair plots

These visualizations help identify trends and relationships among variables.

---

### 3. Data Preprocessing

Preprocessing steps include:

- Data cleaning
- Feature selection
- Standardization (StandardScaler)
- Dimensionality reduction (optional PCA)

---

### 4. Hierarchical Agglomerative Clustering (CAH)

The CAH method is applied to:

- Build a dendrogram
- Determine the optimal number of clusters
- Analyze hierarchical relationships among countries

Advantages:
- No need to specify the number of clusters initially
- Easy interpretation through dendrograms

---

### 5. K-Means Clustering

The K-Means algorithm is applied to:

- Partition countries into clusters
- Minimize intra-cluster variance
- Identify homogeneous groups

Cluster selection methods:

- Elbow Method
- Silhouette Score

---

### 6. Model Comparison

The clustering approaches are compared using:

- Silhouette Score
- Cluster cohesion
- Cluster separation
- Interpretability
- Humanitarian relevance

---

## Repository Structure

```bash
Humanitarian-Country-Clustering/
│
├── data/
│   └── Country-data.csv
│
├── notebooks/
│   └── Country_Clustering.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── dendrogram.png
│   ├── elbow_method.png
│   └── clusters.png
│
├── report/
│   └── final_report.pdf
│
├── README.md
└── requirements.txt
```
---
# Technologies Used
## Programming Language
* Python
## Libraries
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
---
# Key Analyses
## Exploratory Data Analysis
* Statistical summaries
* Variable distributions
* Correlation analysis
## Clustering Techniques
* Hierarchical Agglomerative Clustering (CAH)
* K-Means Clustering
## Evaluation Metrics
* Silhouette Score
* Within-Cluster Sum of Squares (WCSS)
* Dendrogram Analysis
---
## Expected Outcomes

The project enables:

- Identification of vulnerable countries
- Country segmentation based on development indicators
- Comparison of clustering methodologies
- Support for humanitarian decision-making

Countries belonging to clusters characterized by:

- High child mortality
- Low GDP per capita
- Low life expectancy

can be considered priority candidates for humanitarian assistance.
---
## Results

The analysis highlights distinct groups of countries with varying levels of socioeconomic development.

The comparison between CAH and K-Means provides insights into:

* Cluster stability
* Cluster interpretability
* Practical applicability for humanitarian planning
---
# Future Improvements

Potential extensions include:

* Incorporating additional indicators
* Applying Gaussian Mixture Models (GMM)
* Using DBSCAN clustering
* Integrating geographic information
* Developing an interactive dashboard with Streamlit
---
# Author

KGU

Data Science | Machine Learning Engineer
```bash
GitHub: https://github.com/LEROYKGU
```
# License

This project is licensed under the MIT License.
