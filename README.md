# Task 8: Clustering with K-Means

## Overview
In this task, I applied K-Means clustering on the **Mall_Customers** dataset to segment customers based on their demographics and spending behavior.  
I also included the **Gender** feature (already encoded) to see how it influences the clusters.

## Steps I Followed
1. Loaded the dataset and checked for missing values.  
2. Selected features: `Gender`, `Age`, `Annual Income (k$)`, and `Spending Score (1-100)`.  
3. Scaled the data using `StandardScaler` for consistency.  
4. Used the **Elbow Method** to find the optimal number of clusters (K).  
5. Trained the **K-Means** model and assigned cluster labels.  
6. Applied **PCA** for 2D visualization of clusters.  
7. Visualized clusters and centroids using Matplotlib and Seaborn.  
8. Evaluated clustering performance using **Silhouette Score**.

## Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Conclusion
The K-Means model grouped customers into distinct clusters based on income, spending, and age. Including gender helped visualize subtle variations in spending behavior between male and female customers. 
The Silhouette Score showed that the clusters were reasonably well-defined and separable.
