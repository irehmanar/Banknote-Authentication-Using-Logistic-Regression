# Student Performance Prediction: Linear Regression

This repository contains the implementation of a linear regression model for predicting students' mean grades based on various socioeconomic and academic factors. The project highlights the importance of data-driven approaches in understanding and improving educational outcomes.

## **Project Overview**

The primary goal of this project is to predict students' mean grades by leveraging linear regression and analyzing the influence of socioeconomic and academic factors. 

## **Dataset**

The dataset includes the following key features:
- **Student Information**: Age, gender, address type (urban/rural), family size, etc.
- **Parental Information**: Education levels, job types.
- **Academic Records**: Number of past failures, attendance, grades.
- **Lifestyle Factors**: Free time, internet access, alcohol consumption.

The target variable is the students' mean grade (`mean_g`).

## **Implementation**

### **Steps Involved**
1. **Data Preprocessing**: 
   - Handling missing values.
   - Encoding categorical variables.
   - Feature scaling and normalization.

2. **Exploratory Data Analysis (EDA)**:
   - Identifying key factors influencing student performance.
   - Visualizing correlations and distributions.

3. **Model Development**:
   - Implemented Linear Regression for predicting grades.
   - Regularized models (Ridge regression) to address multicollinearity.

4. **Model Evaluation**:
   - Metrics used include Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²).

### **Key Findings**
- The linear regression model's performance:
  - **MSE**: 10.8899
  - **RMSE**: 10.8899
  - **MAE**: 2.7512
  - **R²**: 0.3004
- Ridge regression slightly improved the model’s R² to 0.3020.
- Significant predictors include parental education, number of failures, and socioeconomic factors.

## **Requirements**

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the requirements using:
```bash
pip install -r requirements.txt
