# Assignment 6: Regression on Dataset

**Objective:** Predict a continuous target variable using Linear Regression.

**Orange Workflow:**
1. **File Widget:** Load a dataset with a continuous target variable (e.g., `housing.tab`).
2. **Data Sampler Widget:** Connect File to Data Sampler to split data (e.g., 80% training, 20% testing).
3. **Linear Regression Widget:** Connect the training data from the Data Sampler to this model widget.
4. **Test and Score Widget:** 
   - Connect the **Data Sampler** (Test Data) to the Data input.
   - Connect the **Linear Regression** widget to the Learner input.
   - Evaluate metrics like RMSE, MAE, and $R^2$.
5. **Predictions Widget:** Connect the model and test data to view actual vs. predicted values.
