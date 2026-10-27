# Assignment 3: Data Transformation

**Objective:** Normalize or discretize data to prepare it for machine learning algorithms.

**Orange Workflow:**
1. **File Widget:** Load your dataset.
2. **Preprocess Widget:** Connect the File widget to Preprocess.
   - Add **Normalize Features** (e.g., Standardize to $\mu=0, \sigma=1$ or scale to $[0,1]$).
   - Add **Discretize Continuous Variables** if you need to convert numerical data into categorical bins (e.g., Equal frequency/Equal width).
3. **Distributions Widget:** Visualize the transformed variables to confirm their new scales or bins.
