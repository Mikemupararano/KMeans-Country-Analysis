# KMeans-Country-Analysis
This project applies KMeans clustering to country data to classify countries into different groups based on various socio-economic indicators. The analysis helps to visualize and understand the economic development levels of different countries.

## Table of Contents
Introduction
Dataset
Project Steps
Results
Requirements
Usage
Contributing
License

## Introduction
This project uses the KMeans clustering algorithm to analyze and group countries based on their socio-economic indicators such as GDP per capita, child mortality, inflation, and others. The primary objective is to identify clusters that can provide insights into the economic development stages of different countries.

## Dataset
The dataset used in this project is Country-data.csv. It contains various indicators for multiple countries, including:

Child mortality (per 1000 births)
Exports (% of GDP)
Health (% of GDP)
Imports (% of GDP)
Income per person
Inflation (annual %)
Life expectancy (years)
Total fertility rate (children per woman)
GDP per capita (USD)

## Project Steps
Load the Dataset: Load the Country-data.csv dataset.
Data Cleaning: Drop any non-numeric columns (e.g., country names).
Exploratory Data Analysis: Plot scatter plots to understand the relationship between GDP per capita and other indicators.
Normalization: Normalize the dataset using MinMaxScaler from sklearn.
Determine Optimal Clusters: Use the elbow method and silhouette scores to find the optimal number of clusters.

Clustering: Apply KMeans clustering to the normalized data.
Evaluation: Report the silhouette score for the chosen number of clusters.
Visualization: Visualize the clusters with scatter plots for key indicators:
Child mortality vs GDP per capita
Inflation vs GDP per capita
Labeling: Assign labels to clusters based on the indicators to categorize countries into different development stages.

## Results
The analysis resulted in clustering countries into three main groups:

Least Developed: High child mortality, low GDP per capita, high inflation.
Developing: Moderate child mortality, moderate GDP per capita, moderate inflation.
Developed: Low child mortality, high GDP per capita, low inflation.
These labels help to understand the economic conditions and development stages of the countries in the dataset.

## Requirements

Python 3.7+
pandas
numpy
matplotlib
scikit-learn
Jupyter Notebook
You can install the required packages using:
pip install pandas numpy matplotlib scikit-learn notebook

## Usage
Clone the repository:
bash
Copy code
git clone https://github.com/Mhikemupararano-username/KMeans-Country-Analysis.git
cd KMeans-Country-Analysis
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook Kmeans_task.ipynb
Follow the steps in the notebook to perform the clustering analysis.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.