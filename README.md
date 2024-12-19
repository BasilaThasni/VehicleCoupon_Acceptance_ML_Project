# Machine Learning Classification Project

## Overview

This project focuses on solving a classification problem using various machine learning models.The dataset is about the details of passengers who are meant to cehck the possibility of a coupon acceptance.According to various conditions and scenarios,the possibility is checked.The dataset contains 26 columns including the target column.And has 12684 rows.

---

## Project Workflow

1. **Data Loading**:  
   Load the dataset from CSV files and perform an initial exploration of the data.

2. **Data Preprocessing**:  
   Shows the shape of the dataset,the sattistical measures,Also finds if there is duplicated rows and removed them.Removs an unwanted column which has only 108 non null values and it also doesn't correlate with the target column as well.
   Checks if there is null value in any column and removes the rows having null values by resetting the index. 

3. **Encoding**:  
   - Encode the ordered features using OrdinalEncoder.  
   - Encode the unordered features using OneHotEncoder.    

4. **Scaling**:  
   Since there is only one numerical column,only scaling is to be done for a single column.

5. **Feature Selection**:  
   By using correlation matrix,finds some relations.
   Uses selectKBest for further feature selection.

6. **Train-Test Split**:
   Splits the data for training and testing.

7. **Model Implementation**: 
   Implements 5 classification models.
   ~ Logistice Regression.
   ~Decision Tree Classifier.
   ~Random Forest Classifier.
   ~SVM.
   ~Gradient Boosting.
    
9. **Hyperparameter Tuning**:
   Tries hyperparameter tuning because of the less accuracy by the classification report of each model.
    
##The best model has been selected##


