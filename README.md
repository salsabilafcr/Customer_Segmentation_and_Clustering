# Segment Shopping Customers using KMeans Clustering
This data analysis portfolio project contains customer segmentation using the Mall Customers dataset. Here I performed best cluster identification using KMeans unsupervised machine learning algorithm to find univariate and bivariate clusters. Once these clusters were identified, summary statistics were performed to identify the best marketing groups. 


## Problem Statement
The marketing team aims to develop a targeted strategy to enhance customer engagement and satisfaction. To achieve this, it is crucial to identify distinct shopping groups within the customer base at the mall. The primary focus is on understanding the key segments based on income, age, and shopping score. 


## Objective Segmentatins
Determine the optimal number of customer groups and assign labels to each group. By gaining insights into these segments, the marketing team can tailor their strategies, promotions, and services to better meet the specific needs and preferences of each identified group. This targeted approach is expected to improve customer satisfaction, increase loyalty, and drive overall business success.


## Customer Segmentation and Clustering Process
Customer segmentation and clustering process involves the following steps:
1. **Variables Selection** - Select the variables that will be used for clustering. Ensure that the variables are appropriate for the purpose of the analysis and the characteristics of the data. This project uses 2 clustering techniques, namely univariate-clustering using one variable which is 'Annual Income (k$)'. And bivariate-clustering using two variables namely 'Annual Income (k$)', 'Spending Score (1-100)'.
2. **Univariate and Bivariate Analysis** - Conduct univariate analysis to determine data distribution, data characteristics, and also detect outliers. Then, conduct a bivariate analysis to determine the relationship between variables.
3. **Determine The Number of Clusters (k)** - Determine the number of clusters using methods such as Elbow Method or Silhouette Score to find the optimal K value. In this analysis I used the Elbow Method to find the number of clusters by determining the elbow point.
4. **KMeans iteration** - Conduct K-Means iterations until convergence or up to the specified number of iterations. At each iteration, the data is assigned to the nearest cluster and the cluster center is updated.
5. **Result Interpretation** - Interpret the clustering results. Identify cluster characteristics and how the selected variables affect cluster formation.


## Univariate and Bivariate Clustering Results
### Univariate Clustering Results
In this univariate clustering I only use one variable, the variable 'Annual Income (k$)'. The clustering results will provide groups of customers or observations based on their income level.
![alt text](https://github.com/salsabilafcr/Customer_Segmentation_and_Clustering/blob/main/Univariate%20Clusters.png?raw=true)

**Cluster Interpretations :**
From the clustering results using one variable (univariate) there is not much information that we can get. However, if you notice that cluster 1 has the highest income and expenditure score compared to the other two clusters. Therefore, the marketing team can focus on conducting campaigns in this cluster. And do more promotions for the other two clusters to increase shopping interest.

**Disclaimer!** It should be noted that univariate clustering may provide limited understanding as only one dimension is considered. In most cases, multivariate clustering (using multiple variables) is more informative as it can account for variations in multiple dimensions, providing better and more accurate segmentation. In this case I used bivariate clustering to determine the target cluster.


### Bivariate Clustering Results
In this bivariate clustering, I used two variables, namely the 'Annual Income (k$)' and 'Spending Score (1-100)' variables. The clustering results will provide groups of customers or observations based on their income level and spending score.
![alt text](https://github.com/salsabilafcr/Customer_Segmentation_and_Clustering/blob/main/Bivariate%20Clusters.png?raw=true)

![alt text](https://github.com/salsabilafcr/Customer_Segmentation_and_Clustering/blob/main/Cluster.png?raw=true)

**Cluster Interpretations :**
- Target group would be cluster 3 which has a high spending score and high income.
- 53% of cluster 3 shoppers are women. We should look for ways to attract these customers using marketing campaign targeting popular items in this cluster.
- Cluster 4 presents an interesting opportunity to market to the customers for sales event on popular items.



