# Countries Clustering using Machine Learning

## Project Overview
This project analyzes socio-economic indicators of countries to identify those that require the most financial aid. Machine learning clustering techniques were used to group countries based on economic and health indicators.

## Problem Statement
GIVE Foundation is an NGO that provides financial aid to underdeveloped countries. After receiving $10 million in funding, the CEO must decide which countries need aid the most. This project uses clustering algorithms to identify the countries that require financial assistance.

## Dataset
The dataset contains information for **167 countries** with the following variables:

- GDP per capita (gdpp)
- Income
- Child mortality
- Life expectancy
- Inflation
- Exports and imports

## Techniques Used
- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- K-Means Clustering
- Hierarchical Clustering
- Elbow Method for selecting optimal clusters

## Results
Countries were categorized into three clusters:

- Developed countries
- Developing countries
- Underdeveloped countries

Cluster 2 contained countries with very low income and high child mortality rates.

## Countries Recommended for Financial Aid
- Burundi
- Liberia
- Congo (Democratic Republic)
- Niger
- Sierra Leone

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook
