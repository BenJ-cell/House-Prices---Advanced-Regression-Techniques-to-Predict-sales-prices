# House Prices - Sales Prediction with XGBoost GridSearch vs HalvingGridSearch vs RandomizedSearch vs HalvingRandomSearch

## Contents:

1. **[X, y Summary](#DF)**
    * Import Libraries
    * Read the data
    * X, y info
    * Correlation between features and target on heatmap
    
2. **[Data Cleaning](#Clean)**
    * Remove the columns with more than half missing values
    * Drop columns with most of the rows having only one category
    
3. **[Feature Engineering](#Feature)**
    * Create New Numerical Features
    * Create New Boolean Features
    * Replace ordered categories with numbers
    * Create features using mathematical transformations
    * Create feature using count
    * Create feature using group transforms
    * Drop high cordinality categorical columns
    * Handle rare categorical values
    * Create features using feature interactions
    * Impute numerical columns
    
4. **[Data Visualization](#Viz)**
    * Distribution of top 5 features correlated with Sales Price
    
5. **[Feature Selection](#Select)**
    * Selecte Features
    
6. **[Model Creation](#Model)**
    * Grid Search
    * HalvingGridSearchCV
    * RandomizedSearchCV
    * HalvingRandomSearchCV
    
7. **[Training and Testing Model](#Test)**
    * Best Parameters
    * Feature Importance
