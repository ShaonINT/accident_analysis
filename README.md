# Accident Analysis Report

This repository contains an in-depth analysis of traffic accidents, focusing on identifying significant patterns, exploring influential variables, and developing machine learning models to enhance road safety measures.

## Objectives

1. **Accident Timing Analysis**: Identify significant hours of the day and days of the week when accidents are most frequent.
2. **Motorbike Accident Patterns**: Examine motorbike-related accidents to identify timing trends.
3. **Pedestrian Accidents**: Analyze pedestrian-involved accidents for timing significance.
4. **Variable Impact**: Explore how factors like speed limit, weather, road surface conditions, light conditions, and skidding impact accident severity.
5. **Accident Clusters**: Identify clusters of accidents in the Kingston Upon Hull region.
6. **Outlier Detection**: Detect unusual entries in the dataset using outlier detection techniques.
7. **Classification Models**: Develop models to predict fatal injuries in accidents, aiming to inform and improve road safety strategies.

## Project Features

- **Data Analysis**: Exploratory data analysis (EDA) to understand patterns and trends.
- **Machine Learning**: Classification models such as Random Forest and Logistic Regression for accident severity prediction.
- **Clustering**: Identifying accident hotspots using K-Means and DBSCAN.
- **Outlier Detection**: Leveraging techniques like Isolation Forest and Local Outlier Factor.
- **Data Visualization**: Visual representation of accident trends and patterns.

## Tools and Technologies

- **Languages**: Python
- **Libraries**: 
  - Data Analysis: `pandas`, `numpy`, `scipy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `mlxtend`
  - Clustering: `KMeans`, `DBSCAN`, `AgglomerativeClustering`
- **Database**: SQLite

## Structure

- **Notebook**: `Big Data & Data Mining Assignment.ipynb` contains all the code and analysis.
- **Dataset**: The dataset used for this project focuses on traffic accidents in Kingston Upon Hull.
- **Models**: Classification and clustering models for accident analysis and prediction.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/accident_analysis.git