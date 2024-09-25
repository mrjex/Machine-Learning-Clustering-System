# Machine Learning Clustering System 🤖

> Advanced Customer Segmentation using Unsupervised Learning Techniques

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

## 📑 Table of Contents

- [Machine Learning Clustering System 🤖](#machine-learning-clustering-system-)
  - [📑 Table of Contents](#-table-of-contents)
  - [🎯 Overview](#-overview)
  - [🔑 Key Features](#-key-features)
  - [🏗 System Architecture](#-system-architecture)
  - [📊 Methodology](#-methodology)
    - [Exploratory Data Analysis](#exploratory-data-analysis)
    - [Dimensionality Reduction](#dimensionality-reduction)
    - [Cluster Evaluation](#cluster-evaluation)
    - [Advanced Cluster Analysis](#advanced-cluster-analysis)
  - [📈 Results and Conclusions](#-results-and-conclusions)
  - [📁 Project Structure](#-project-structure)
  - [🚀 Getting Started](#-getting-started)
  - [💼 Portfolio](#-portfolio)

## 🎯 Overview

This project, developed during my exchange semester in Italy (October 2024 - January 2025), demonstrates the application of advanced machine learning techniques for customer segmentation. The system analyzes a complex dataset comprising 2,240 customer profiles across 29 dimensions, employing sophisticated clustering algorithms to uncover meaningful patterns and customer segments.

## 🔑 Key Features

- **Dimensionality Reduction:** Implementation of Principal Component Analysis (PCA) for efficient feature space transformation
- **Clustering Algorithms:**
  - K-Means Clustering
  - Spectral Clustering
  - Agglomerative Clustering
- **Optimization:** Elbow Method for optimal cluster determination
- **Quality Assessment:** Silhouette Score analysis for cluster validation
- **Interactive Analysis:** Configurable clustering parameters (K=2 to 10)
- **Comprehensive Visualization:** Multi-dimensional data representation

## 🏗 System Architecture

Our system follows a modular architecture designed for maximum flexibility and scalability:

![architecture](readme-material/architecture.PNG)

## 📊 Methodology

### Exploratory Data Analysis

Our initial analysis revealed fascinating patterns in customer education levels and spending behaviors:

![education](readme-material/1-education.PNG)
*Distribution of customer education levels*

![education-spendings](readme-material/2-education-levels-income.PNG)
*Correlation between education levels and income*

![martial-status-spending](readme-material/3-marital-status-spending.PNG)
*Spending patterns across marital status groups*

### Dimensionality Reduction

We employed PCA to reduce data complexity while preserving essential information:

![dimensionality-reduction](readme-material/4-dimensionality-reduction.PNG)

*PCA transformation results*

![dimensionality-reduction-clusters](readme-material/5-dimenstionality-reduction-clusters.PNG)

*Cluster visualization in reduced dimensions*

![elbow-method](readme-material/6-elbow-method.PNG)

*Optimal cluster determination using the Elbow Method*

### Cluster Evaluation

Rigorous evaluation of clustering performance using multiple metrics:

![silhouette-score](readme-material/7-silhouette-score.PNG)

*Silhouette analysis of cluster quality*

![silhouette-score-table](readme-material/8-silhouette-score.PNG)

*Comparative performance of clustering algorithms*

### Advanced Cluster Analysis

Detailed analysis of the configured clustering method revealed distinct customer segments:

![cluster-income-spendings](readme-material/9-cluster-income-spendings.PNG)

*Income vs. Spending patterns by cluster*

![cluster-deals-purchased](readme-material/10-cluster-deals-purchased.PNG)

*Deal purchase behavior analysis*

![feature-comparisons](readme-material/11-feature-comparisons.PNG)

*Multi-feature cluster comparison*

![age-distribution](readme-material/12-age-distribution.PNG)

*Age distribution across clusters*

## 📈 Results and Conclusions

Our analysis yielded actionable insights into customer segments:

![cluster-characteristics](readme-material/cluster-characteristics.PNG)

*Key characteristics of identified customer segments*

## 📁 Project Structure

```
project/
│
├── code.ipynb          # Main Jupyter notebook with analysis
├── docs/
│   └── report.pdf      # Detailed methodology and findings
└── readme-material/    # Visualization assets
```

## 🚀 Getting Started

1. Clone the repository
2. Install required dependencies
3. Open `project/code.ipynb` in Jupyter Notebook
4. Explore the analysis or modify parameters as needed

For detailed implementation insights, refer to:
- 📘 [Code Documentation](code_part_1.ipynb)
- 📊 [Full Analysis Report](/docs/report.pdf)

## 💼 Portfolio

Here are some of my other data science and machine learning projects:

- [🔍 Relational Analysis And Visualization](https://github.com/mrjex/Relational-Analysis-and-Visualization): *Machine Learning Prediction Model with Linear Regression*
- [📊 Realtime Change Data Capture Streaming](https://github.com/mrjex/Realtime-Data-Capture-Streaming): *Real-time Data Pipeline and Visualization*
- [🌍 Global City Streaming](https://github.com/mrjex/Global-City-Streaming): *Multi-dimensional Data Visualization Pipeline*
- [📈 Tableau Visualization](https://github.com/mrjex/Tableau-Visualization): *SQL Data Model Transformation and Visualization*
- [🤖 Artificial Intelligence Clusters](https://github.com/mrjex/Artificial-Intelligence-Clusters): *Unsupervised Learning for Data Segmentation*
- [🧠 Neural Network Image Classification](https://github.com/mrjex/Neural-Network-Image-Classification): *Deep Learning for Image Recognition*
- [📊 US Political & Societal Data Visualization](https://github.com/mrjex/US-Political-and-Societal-Data-Visualization): *Python-based Data Visualization*
- [🎯 Artificial Intelligence Classifiers](https://github.com/mrjex/Artificial-Intelligence-Classifiers): *Supervised Learning Models*

---

*This project is part of my advanced machine learning portfolio, developed during my exchange semester at the University of Ca' Foscari in Italy, Venice.*