# Clustering Algorithms

This folder contains unsupervised machine learning clustering algorithms implemented using Python and Scikit-learn.

The notebooks demonstrate:
- cluster creation
- cluster visualization
- distance-based clustering
- density-based clustering
- dendrogram interpretation
- cluster validation
- parameter tuning

---

# Algorithms Included

## 1. K-Means Clustering

### Objective
Group data points into clusters using centroid-based clustering.

### Concepts Demonstrated
- Elbow Method
- WCSS
- KneeLocator
- Cluster visualization
- Silhouette Score

### File
- `kmeans/kmeans_clustering.ipynb`

---

## 2. Hierarchical Clustering

### Objective
Understand hierarchical grouping of data using agglomerative clustering.

### Concepts Demonstrated
- PCA for visualization
- Dendrogram
- Ward linkage
- Agglomerative Clustering
- Silhouette Score

### File
- `hierarchical-clustering/hierarchical_clustering.ipynb`

---

## 3. DBSCAN Clustering

### Objective
Identify clusters based on density and detect noise points.

### Concepts Demonstrated
- Density-based clustering
- `eps`
- `min_samples`
- k-distance graph
- Noise/outlier detection
- Cluster visualization

### File
- `dbscan/dbscan_clustering.ipynb`

---

# Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- scipy
- kneed

---

# Key Learnings

These projects helped me understand:
- how unsupervised learning groups data without labels
- how different clustering algorithms behave
- when to use K-Means, Hierarchical Clustering, and DBSCAN
- how to choose cluster count or clustering parameters
- how to validate clustering quality using visualization and silhouette score