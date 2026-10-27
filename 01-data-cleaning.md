# Assignment 1: Data Cleaning

**Objective:** Handle missing values and noisy data in a dataset.

**Orange Workflow:**
1. **File Widget:** Load your dataset (e.g., `heart_disease.tab` which contains missing values).
2. **Preprocess Widget:** Connect the File widget to Preprocess. 
   - Add the **Impute Missing Values** module.
   - Select a method (e.g., "Average/Most frequent" or "Model-based imputer").
3. **Data Table Widget (x2):** Connect one to the original File widget and one to the Preprocess widget to compare the dataset before and after cleaning.
