# Assignment 9: Clustering Rule Process on iris.arff

**Objective:** Apply Simple K-Means on an ARFF formatted Iris dataset and analyze the cluster rules/characteristics.

**Orange Workflow:**
1. **File Widget:** Download `iris.arff` online and load it using the File widget (Orange supports `.arff` natively).
2. **K-Means Widget:** Connect the File widget. Set k=3. 
3. **Silhouette Plot Widget:** Connect K-Means here to evaluate the tightness and separation of the 3 clusters.
4. **Data Table Widget:** Connect K-Means to Data Table to observe the appended "Cluster" column.
5. **Box Plot Widget:** Connect the K-Means output here. Subgroup the variables by "Cluster" to deduce the rules (e.g., "Cluster 1 always has Petal Length < 2.5").
