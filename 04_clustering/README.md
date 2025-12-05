**Country Socio-Economic Segmentation**
This project applies K-Means Clustering to group countries based on various socio-economic and health indicators.

**Project Objective**

The main objectives of this project are:

Understand the socio-economic patterns of different countries

Preprocess and scale the dataset

Apply K-Means Clustering

Determine the optimal number of clusters using the Elbow Method and Silhouette Score

Visualize and interpret cluster results

Generate actionable insights for policy and global development planning

**Dataset Description**
| Feature        | Description                                                           |
| -------------- | --------------------------------------------------------------------- |
| **country**    | Name of the country                                                   |
| **child_mort** | Child mortality: deaths of children under age 5 per 1,000 live births |
| **exports**    | Exports as a % of GDP per capita                                      |
| **health**     | Total health spending as % of GDP                                     |
| **imports**    | Imports as a % of GDP per capita                                      |
| **income**     | Average income per person                                             |
| **inflation**  | Inflation rate (%)                                                    |
| **life_expec** | Average life expectancy (years)                                       |
| **total_fer**  | Fertility rate (average children per woman)                           |
| **gdpp**       | GDP per capita (measure of economic performance)                      |

K-Means Clustering
1. Finding Optimal K

Two major techniques were used:

--Elbow Method

Plotted SSE (Sum of Squared Errors) against varying K values

Observed the "bend" in the curve to choose optimal K
-- Silhouette Score

Measured how well each point fits its assigned cluster vs. other clusters

Both methods guided the selection of the final number of clusters.

**Technologies Used**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn (StandardScaler, KMeans, Silhouette Score)

Jupyter Notebook
