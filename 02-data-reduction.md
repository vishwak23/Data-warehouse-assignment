# Assignment 2: Data Reduction

**Objective:** Reduce the dimensionality or volume of the data while maintaining its integrity.

**Orange Workflow:**
1. **File Widget:** Load a high-dimensional dataset.
2. **PCA (Principal Component Analysis) Widget:** Connect the File widget to PCA.
   - Adjust the variance covered (e.g., 95%) to reduce the number of features while retaining information.
   - *Alternative:* Use the **Select Columns** widget to manually drop irrelevant features.
3. **Data Table Widget:** Connect the PCA widget to view the newly transformed, reduced dataset components.
