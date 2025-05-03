# Svitlana Kozlovska student of Principles of Data Analytics

by Svitlana Kozlovska

## Iris Dataset Exploration and Analysis

This repository contains a detailed analysis of the Iris dataset using Python.
The project is structured as a Jupyter Notebook (tasks.ipynb) that walks through various tasks, 
from data sourcing to visualization and statistical analysis.

## Table of Contents

1. Introduction
2. Project Overview
3. Tasks Overview
4. Setup Instructions
5. Acknowledgments
6. Technologies
7. Setup Instructions

## Introduction

The Iris dataset is a classic dataset used for machine learning and statistical analysis. 
It contains measurements of sepal and petal lengths and widths for three species of iris flowers: setosa, versicolor, and virginica.
This project explores and analyzes this dataset to demonstrate various data analysis and visualization techniques.

## Project Overview

This project is implemented in a Jupyter Notebook (`tasks.ipynb`) and covers the following objectives:

 - Data sourcing and loading: Using the `sklearn.datasets` module to load the Iris dataset.
 - Exploratory Data Analysis: Exploring the structure, features, and distributions of the dataset.
 - Data visualization: Creating histograms, scatter plots, and pair plots to understand relationships between features.
 - Statistical analysis: Calculating summary statistics, correlations, and fitting regression models.
 - Machine learning readiness: Preparing the data for further machine learning tasks.

## Tasks Overview

#### Task 1: Source the Dataset
 - Import the Iris dataset using the load_iris() function from sklearn.datasets.
 - Understand what the dataset contains (features, targets, descriptions).

#### Task 2: Explore the Data Structure
 - Print the shape of the dataset.
 - Display the first and last 5 rows of the data.
 - List feature names and target classes.

#### Task 3: Summarize the Data
 - Calculate summary statistics: mean, median, minimum, maximum, and standard deviation for each feature.

#### Task 4: Visualize Features
 - Plot histograms for all features using `matplotlib`.

#### Task 5: Investigate Relationships
 - Create `scatter plots` for feature pairs to understand relationships, e.g., petal length vs. petal width.

#### Task 6: Analyze Relationships
 - Fit a linear regression model between features and calculate the coefficient of determination (R²).

#### Task 7: Analyze Class Distributions
 - Visualize the distribution of features across different classes using box plots.

#### Task 8: Compute Correlations
 - Calculate the correlation coefficients between features and visualize them as a heatmap.

#### Task 9: Fit a Simple Linear Regression
 - Fit a regression line between two features and annotate it with R².

#### Task 10: Too Many Features
 - Use `seaborn` to create a pair plot of all features color-coded by class.

## Acknowledgments
The Iris dataset is provided by the UCI Machine Learning Repository.
This project uses tools like scikit-learn, numpy, matplotlib, and seaborn for analysis and visualization. 

## Technologies

- Python
- Git
- GitHub
- Codespaces
- Jupiter

## Setup Instructions

1. Clone repository
```bash
git clone https://github.com/Svitlana937/Svit_Koz_DA.git
cd Svit_Koz_DA

2. Install dependencies: Ensure you have Python 3 installed. Install the required libraries using `pip`:
```bash
jupyter notebook tasks.ipynb
