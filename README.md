# Hierarchical Clustering on Vehicle Dataset

This project performs hierarchical clustering on a vehicle dataset to group vehicles based on similarity in fuel efficiency characteristics. The goal is to gain insights for optimization of vehicle design and manufacturing process.

## Introduction

This project is going to find the most distinctive clusters of vehicles. The datasets of this project contain 16 explanatory variables describing (almost) every aspect of different vehicle brands for each manufacturing company. Exploratory Data Analysis (EDA) method is used to describe the data, viewing the distribution of the data. Then Machine Learning method, Hierarchical Clustering, is used to create a model which can cluster vehicle samples in dataset. In this notebook, we use agglomerative algorithm in Scikit-learn library to solve the problem, which is more popular in doing hierarchical clustering since it's a bottom up approach.

## Dataset

The dataset used is from Kaggle and contains fuel consumption and 10 attributes for 398 different vehicle models from 1999 and 2008. The attributes include number of cylinders, engine size, horsepower etc.

The online link to the original dataset on Kaggle is [available here](https://www.kaggle.com/code/skyecai/hierarchical-clustering-on-vehicle-dataset).

## Objective

The objectives are: 

1. Identify natural groupings or hierarchies among vehicles based on their attributes.

2. Understand profiles of vehicle clusters to optimize designing and manufacturing of green vehicles.

3. Extract relationships between different variables and design parameters affecting fuel consumption.

## Methodology

1. Data preprocessing and standardization

2. Build hierarchical clustering dendrogram using AgglomerativeClustering 

3. Choose optimal number of clusters 

4. Analyze clusters and annotate dendrogram 

5. Provide conclusions on groups, fuel-efficient designs etc.

## Key Insights

The analysis reveals distinct vehicle groupings having:

- High/low cylinder count 
- Engine sizes optimized for fuel efficiency
- Horsepower bands indicating average/powerful designs

Manufacturers can leverage clusters to streamline green vehicle R&D and production planning.

## Requirements

- Python
- Scikit-learn
- Pandas, NumPy, Matplotlib
