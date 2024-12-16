# Heart Disease Prediction Project

## Overview
This project leverages machine learning to predict heart disease based on clinical and demographic data. Key features include age, cholesterol levels, chest pain type, and more. The aim is to assist healthcare professionals in early detection and management of heart disease.

## Project Structure
- **Dataset**: Clinical data with 296 cleaned samples and 14 features (13 predictors + 1 target variable).
- **Notebook**: Includes exploratory data analysis (EDA), modeling, and interpretations.
- **Write-Up**: Detailed analysis and findings are documented within the notebook.

## Key Steps
1. **Data Cleaning**:
   - Removed faulty rows based on domain knowledge.
   - Ensured no missing values.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features and the target variable.
   - Identified key predictors: 
     - Major Vessels
     - Maximum Heart Rate
     - ST Depression
     - Chest Pain Type.

3. **Modeling**:
   - Tested multiple classification models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Tree
     - Random Forest
   - Evaluated performance using:
     - Accuracy
     - Precision
     - Recall
     - F1-Score.

4. **Findings**:
   - Logistic Regression demonstrated the best balance of precision and recall.
   - Random Forest excelled in recall and provided insights into feature importance.


