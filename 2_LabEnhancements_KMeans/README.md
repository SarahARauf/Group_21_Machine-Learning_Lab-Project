# Lab Enhancement: Hierarchical Clustering and DBSCAN

----------------------------------------------------------------------------------------------------------------------

##In this lab enhancement, the following are done:

- Definition of Clustering and its role in unsupervised learning.
- Application of Hierarchical Clustering using the Agglomerative Clustering Algorithm on customer data from the Mall_Customers.csv dataset.
- Exploratory Data Analysis (EDA)
- Visualizing the standardized data using a heatmap
- Generating a dendrogram using hierarchical clustering with the Ward method
- Performing hierarchical clustering with 5 clusters using Agglomerative Clustering. Obtaining cluster labels and assigning them to the DataFrame.
- Creating a 3D scatter plot to visualize clusters based on 'Age,' 'Spending Score (1-100),' and 'Annual Income ' using Plotly.
- Creating a 2D scatter plot to visualize clusters based on 'Annual Income' and 'Spending Score (1-100)' using Matplotlib.
- Calculated and interpreted internal clustering evaluation metrics, including the Silhouette Score, Calinski and Harabasz Score, and Davies-Bouldin Score
- Implemented Density-Based Spatial Clustering of Applications with Noise (DBSCAN) on the standardized mall data.

----------------------------------------------------------------------------------------------------------------------



## Overview

This lab enhancement focuses on Hierarchical Clustering using the Agglomerative Clustering Algorithm and Density-Based Spatial Clustering of Applications with Noise (DBSCAN) on customer data from the Mall_Customers.csv dataset. The notebook covers various aspects, including exploratory data analysis (EDA), data visualization, and internal clustering evaluation metrics.


----------------------------------------------------------------------------------------------------------------------


## Hierarchical Clustering

In this section, we perform Hierarchical Clustering using the Agglomerative Clustering Algorithm on customer data from the Mall_Customers.csv dataset.

### Key Steps:

1. **Exploratory Data Analysis (EDA):** Analyzing the structure and summary statistics of the dataset.

2. **Data Visualization:**
   - Visualizing standardized data using a heatmap.
   - Generating a dendrogram using hierarchical clustering with the Ward method.
   - Performing hierarchical clustering with 5 clusters using Agglomerative Clustering.
   - Creating 3D and 2D scatter plots to visualize clusters based on selected features.

3. **Internal Clustering Evaluation:**
   - Calculating and interpreting internal clustering evaluation metrics, including Silhouette Score, Calinski and Harabasz Score, and Davies-Bouldin Score.

-------------------------------------------------------------------------------------------------------------------------

## DBSCAN

In this section, we implement DBSCAN on the standardized mall data.

### Key Steps:

1. Standardizing the data.

2. Applying DBSCAN with chosen values for `eps` and `min_samples`.

3. Visualizing the clusters using a scatter plot.

4. Evaluating clustering performance with Silhouette Score, Calinski and Harabasz Score, and Davies-Bouldin Score.

----------------------------------------------------------------------------------------------------------------------


## Internal Measures

Internal clustering evaluation metrics provide insights into clustering quality. In this notebook, we use the following metrics:

1. **Silhouette Score:** Measures how well-separated the clusters are, ranging from -1 to 1. A higher score indicates better-defined clusters.

2. **Calinski and Harabasz Score:** Evaluates the ratio of between-cluster dispersion to within-cluster dispersion. A higher score suggests well-separated clusters.

3. **Davies-Bouldin Score:** Measures the average similarity of each cluster with its most similar cluster. Lower values indicate better clustering.

----------------------------------------------------------------------------------------------------------------------



* explanation, description and docomentation are done in the notebook itself.

----------------------------------------------------------------------------------------------------------------------

**END OF README.MD**
