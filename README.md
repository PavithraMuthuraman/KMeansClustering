# K Means Clustering
*K-Means Clustering for Country Grouping*

## Description
This project focuses on grouping countries into clusters based on their geographical coordinates (latitude and longitude) using the K-Means Clustering algorithm. The dataset includes information on various countries, their latitude, longitude, and primary language spoken.

## Project Overview
- **Objective**: Group countries into clusters based on their latitude and longitude to identify geographical regions with similar attributes.
- **Model**: K-Means Clustering is employed to categorize countries into distinct groups.
- **Dataset**: The dataset includes features such as the country's name, latitude, longitude, and the primary language spoken.

## Files Included
- **Country_clusters.csv**: The dataset used for clustering the countries.
- **KMeansClustering.ipynb**: The Python script that performs data preprocessing, model training, and clustering.

## Code Execution
1. **Setup Environment**: Install the required libraries (`numpy`, `pandas`, `scikit-learn`).
2. **Data Loading**: Place `Country_clusters.csv` in the appropriate directory, then load and inspect the dataset.
3. **Preprocessing**: Select the relevant features (latitude and longitude) for clustering.
4. **Model Training**: Train the K-Means Clustering model on the selected features, by setting the number of clusters to 3.
5. **Clustering**: Predict the cluster (0, 1, 2) for each country based on their geographical coordinates.
6. **Analysis**: Analyze the resulting clusters to interpret the geographical groupings.
