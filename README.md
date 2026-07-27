# Advanced Big Data and Data Mining (MSCS-634-B01) - Lab 5: Hierarchical and DBSCAN Clustering Analysis

## Purpose
This repository contains the complete implementation and evaluation of unsupervised machine learning algorithms—specifically **Agglomerative Hierarchical Clustering** and **DBSCAN**—applied to the standard **Wine dataset** from `scikit-learn`.

## Lab Objectives
1. Perform dataset exploration, preprocessing, and standardization using `StandardScaler`.
2. Implement Agglomerative Clustering, evaluate varying cluster counts, and interpret structure via dendrogram visualization.
3. Apply DBSCAN, execute hyperparameter tuning (`eps`, `min_samples`), isolate noise points, and calculate evaluation metrics (Silhouette, Homogeneity, and Completeness scores).
4. Conduct comparative analysis contrasting hierarchical and density-based clustering models.

## Key Insights & Results
* **Hierarchical Clustering:** Proved highly effective for this dataset. Dendrogram analysis clearly indicated **k=3** as the optimal cluster count, matching the ground truth wine classes.
* **DBSCAN:** Demonstrated high sensitivity to the `eps` hyperparameter due to high dimensionality (13 features). Optimal separation occurred at `eps = 2.5` and `min_samples = 5`, effectively isolating true noise/outlier samples.

## File Structure
* `MSCS_634_Lab_5.ipynb` - Complete Python Jupyter notebook with code, comments, visualizations, and comparative reflections.
* `README.md` - Overview, methodology summary, and submission notes.

## Author
* **Course:** Advanced Big Data and Data Mining (MSCS-634-B01)
* **Assignment:** Lab 5
