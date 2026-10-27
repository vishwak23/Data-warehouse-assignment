# Assignment 8: K-Means Algorithm for Iris Dataset

**Objective:** Group Iris flowers into clusters without using the target labels.

**Orange Workflow:**
1. **File Widget:** Load the built-in `iris.tab` dataset.
2. **Select Columns Widget:** (Optional) Move the "iris" class attribute to "Meta Attributes" so the clustering algorithm ignores the true labels.
3. **K-Means Widget:** Connect the data.
   - Set the number of clusters (k=3, corresponding to the 3 iris species).
   - Alternatively, use Silhouette Scores to let Orange auto-determine the best k.
4. **Scatter Plot Widget:** Connect K-Means to Scatter Plot. Color the points by "Cluster" to view the groupings based on petal and sepal dimensions.
