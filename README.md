# Customer-Segmentation-using-Machine-Learning

This repository contains a project that demonstrates customer segmentation using the K-Means clustering algorithm. Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction
Customer segmentation is crucial for businesses to understand their customer base and target them with personalized marketing strategies. This project utilizes the K-Means clustering algorithm to segment customers based on their purchasing behavior and other relevant features.

## Dataset
The dataset used in this project contains the following features:
- **CustomerID**: Unique identifier for each customer
- **Gender**: Gender of each customer
- **Age**: Age of the customer
- **Annual Income**: Annual income of the customer
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature within 1 to 100

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Installation
1. Clone the repo
 ```
 git clone https://github.com/Mayukh-Haldar/Customer-Segmentation-using-Machine-Learning.git
 ```
2. Install the required libraries
```
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Usage
Navigate to the project directory
```
cd Customer-Segmentation-using-Machine-Learning
```
Open the Jupyter Notebook
```
jupyter notebook
```
Open and run the Customer_Segmentation.ipynb notebook to see the customer segmentation in action.
## Results
The project segments customers into different clusters based on their purchasing behavior. The results can be visualized using various plots to understand the characteristics of each cluster. Example output includes:

1. Elbow Method plot to determine the optimal number of clusters.
2. Scatter plots to visualize the clusters.
