# Assignment 7: Outlier Analysis

**Objective:** Detect anomalous data points within a dataset.

**Orange Workflow:**
1. **File Widget:** Load your dataset.
2. **Outliers Widget:** Connect the File widget here.
   - Choose an outlier detection method: **Local Outlier Factor (LOF)** or **Isolation Forest**.
   - Set the contamination rate (e.g., 5% expected outliers).
3. **Scatter Plot Widget:** Connect the Outliers widget to Scatter Plot.
   - Use the "Outlier" meta-attribute as the color/shape to visually distinguish normal data points from identified outliers.
