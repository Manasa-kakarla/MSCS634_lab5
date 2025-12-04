# MSCS 634 - Lab 5: Clustering Analysis on Wine Dataset

---

## Purpose of the Lab

The purpose of this lab is to explore **clustering techniques** on the Wine dataset from `sklearn.datasets`. Specifically, the lab involves:

- Standardizing the dataset features for clustering.  
- Applying **Hierarchical (Agglomerative) Clustering** to identify natural groupings of wines.  
- Applying **DBSCAN Clustering** to detect clusters and noise points without predefining the number of clusters.  
- Evaluating clustering quality using metrics such as Silhouette Score, Homogeneity Score, and Completeness Score.  
- Visualizing and interpreting the results to gain insights into wine groupings.

---

## Key Insights

1. **Hierarchical Clustering**:  
   - Tested multiple `n_clusters` values.  
   - Dendrogram revealed the natural hierarchy of wine samples.  
   - Scatter plots helped visualize cluster separation in feature space.  

2. **DBSCAN Clustering**:  
   - Experimenting with `eps` and `min_samples` showed the algorithm's sensitivity to parameter selection.  
   - Successfully identified clusters and highlighted noise points.  
   - Silhouette, homogeneity, and completeness scores helped assess clustering quality.  

3. **Comparison**:  
   - Hierarchical clustering provides a clear hierarchy but requires specifying the number of clusters.  
   - DBSCAN automatically detects clusters of arbitrary shape and identifies noise but is sensitive to parameter choices.

---

## Challenges and Decisions

- **Feature Scaling**: Standardization was critical because clustering algorithms are distance-based.  
- **DBSCAN Parameters**: Selecting appropriate `eps` and `min_samples` required experimentation.  
- **Visualization**: Reduced high-dimensional data to 2D scatter plots for interpretability.  
- **Cluster Evaluation**: Multiple metrics were used to ensure a comprehensive assessment of clustering quality.

---
**Conclusion:**  
This lab demonstrates the application of different clustering techniques on real-world datasets, emphasizing the importance of parameter selection, feature scaling, and proper evaluation metrics for meaningful clustering results.
**Conclusion:**  
This lab demonstrates the application of different clustering techniques on real-world datasets, emphasizing the importance of parameter selection, feature scaling, and proper evaluation metrics for meaningful clustering results.
