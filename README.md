# Student-Performance-Prediction-using-Regression-
# Student Performance Prediction using Regression

## Overview
This project predicts student performance using machine learning regression models. The dataset includes various study-related factors such as hours studied, previous scores, sleep hours, extracurricular activities, and sample question papers practiced.

## Dataset
The dataset consists of the following features:
- **Hours Studied** (int)
- **Previous Scores** (int)
- **Extracurricular Activities** (categorical)
- **Sleep Hours** (int)
- **Sample Question Papers Practiced** (int)
- **Performance Index** (float, target variable)

## Data Preprocessing
1. **Handling Missing Values**: No missing values were found in the dataset.
2. **Checking for Duplicates**: Removed 127 duplicate rows.
3. **Encoding Categorical Data**: Used `LabelEncoder` for `Extracurricular Activities`.
4. **Feature Scaling**: Applied `StandardScaler` to numerical columns.

## Model Training
- **Train-Test Split**: 80% training, 20% testing.
- **Regression Model Used**: Linear Regression.

## Results
- **Mean Squared Error (MSE)**: `0.01167`
- **R-squared (R²) Score**: `0.9884`

## Conclusion
The regression model achieved a high R² score, indicating excellent predictive performance. Further improvements can be explored using advanced models such as Decision Trees or Random Forest Regression.

## Future Work
- Experiment with different regression models.
- Use feature selection techniques to optimize model performance.
- Perform hyperparameter tuning to enhance accuracy.

## Author
Developed by Speranza Deejoe.
