# Prediction of Concrete Compressive Strength

**Overview**  
This project focuses on predicting the compressive strength of concrete based on its material composition using two approaches:  

**Linear Regression** – as a baseline statistical model  
**XGBoost Regression** – for advanced machine learning performance  

The dataset is sourced from the UCI Machine Learning Repository and reflects real-world applications in civil engineering and material testing.  

**Dataset**  
**Source :** https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength  
**Size :** 1030 Instances, and 9 Input Features.  

**Features :**  
   * Cement (Kg/m^3)
   * Blast Furnance Slag (Kg/m^3)
   * Fly Ash (Kg/m^3)
   * Water (Kg/m^3)
   * Superplasticizer (Kg/m^3)
   * Coarse Aggregate (Kg/m^3)
   * Fine Aggregate (Kg/m^3)
   * Age (days)
   * Target : Compressive Strength (MPa)

**Tools & Technologies**   
**Programming Language :** Python  
**Libraries :**   
   * **Pandas :** Data Handling  
   * **numpy :** Numerical Computation  
   * **matplotlib :** Visualization  
   * **Scikit-learn :** ML Modeling and Performance metrics.
   * **xgboost** – advanced regression modeling  

**Modeling Approaches**  
  **Linear Regression:** Baseline regression model  
  **XGBoost Regression:** Gradient boosting with k=10 fold cross-validation  

**Results**  
   **Linear Regression**   
     R^2 : 0.62  
     MAE (MPa) : 8.21  
     RMSE (MPa) : 10.35  
   **XGBoost Regression**  
     R^2 : 0.96  
     MAE (MPa) : 0.89  
✅ **XGBoost outperformed Linear Regression**, showing strong predictive capability and robustness with cross-validation.  

**Key Insights**  
* Traditional regression provides a baseline but struggles with complex non-linear relationships.  
* XGBoost significantly improves prediction accuracy, highlighting the value of ensemble learning in civil engineering applications.  
* The model demonstrates potential in optimizing raw material usage and predicting mix strength in construction.  


