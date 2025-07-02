# K-Means Clustering 

This repository features Python implementations of the **K-Means Clustering** algorithm, applied to both 2D and higher-dimensional datasets. It demonstrates how K-Means groups data based on Euclidean distance and visualizes the clusters using scatter plots and PCA.

---

## File Overview

| File Name                   | Description                                                  |
|----------------------------|--------------------------------------------------------------|
| `kmeans_2d_2clusters.py`       | Performs clustering on a 2D dataset using `k = 2`                |
| `kmeans_nfeatures_kclusters.py` | Applies K-Means to higher-dimensional data (`n=4`, `k=3`) and uses PCA for plotting |

---

## Clustering Tasks

### 1️⃣ Two-Dimensional Clustering (k = 2)

- **Dataset**: 12 samples with 2 numeric features
- **Clusters**: 2
- **Distance Measure**: Euclidean Distance
- **Outputs**:
  - Cluster assignments for each point
  - Centroids of both clusters
  - Within-Cluster Sum of Squares (WCSS)
  - Scatter plot showing clustering results

---

### 2️⃣ Clustering with Multiple Features (k = 3)

- **Dataset**: 12 data points with 4 attributes
- **Clusters**: 3
- **Distance Measure**: Euclidean Distance
- **Visualization**: Uses PCA (Principal Component Analysis) to reduce to 2D for plotting
- **Outputs**:
  - Cluster labels
  - Calculated centroids
  - WCSS metric
  - 2D visualization using Matplotlib

---

## 🔧 Setup Instructions

You’ll need the following Python libraries:

- Python 3.6 or newer
- `numpy`
- `matplotlib`
- `scikit-learn` (used for PCA in the multi-feature clustering task)

Install them via pip:

```bash
pip install numpy matplotlib scikit-learn
python kmeans_2d_2clusters.py
python kmeans_nfeatures_kclusters.py

