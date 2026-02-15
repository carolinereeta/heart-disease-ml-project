# Heart Disease Prediction Using Machine Learning

## Dataset

Source: Kaggle (Heart Disease Prediction)  
Observations: 10,000 patients  
Target Variable: Heart Disease Status (Yes / No)

### Key Variables:
- Age  
- Gender  
- Blood Pressure  
- Cholesterol Level  
- Diabetes  
- BMI  
- Smoking  
- Exercise Habits  
- Stress Level  
- Sleep Hours  
- CRP Level  
- Homocysteine Level  

---

## Research Questions

1. Which medical and lifestyle factors are most strongly associated with heart disease?
2. Can machine learning accurately predict the presence of heart disease?
3. How does class imbalance affect healthcare model performance?
4. Which features contribute most to model predictions?

---

## Tools and Methods

**Language:** Python  
**Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  

### Methods Used:
- Data cleaning and missing value imputation  
- Exploratory Data Analysis (EDA)  
- One-Hot Encoding of categorical features  
- Stratified train-test split  
- Random Forest classification  
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix  
- Feature importance analysis  

---

## Results and Visualizations

### 1. Target Distribution

Initial analysis revealed class imbalance in the dataset. Class weighting was applied to ensure the model properly identified heart disease cases rather than favoring the majority class.

### 2. Correlation Analysis

Correlation heatmaps indicated relationships between cholesterol, blood pressure, and other risk indicators. While correlation does not imply causation, these relationships informed feature understanding.

### 3. Model Performance

The Random Forest classifier achieved strong overall accuracy on the test set.

However, evaluation emphasized recall and precision rather than accuracy alone, given the healthcare context where missing a positive case (false negative) can have serious implications.

### 4. Feature Importance

Feature importance analysis identified the most influential predictors in the model, providing interpretability and insight into potential risk factors.

---

## Conclusion

This project demonstrates how machine learning can be applied to healthcare risk prediction using structured patient data.

Key takeaways include:
- The importance of handling class imbalance in medical datasets.
- The necessity of evaluating precision and recall rather than relying solely on accuracy.
- The value of feature importance analysis for interpretability in healthcare applications.

While this model does not establish medical causation, it highlights predictive relationships between health indicators and heart disease risk.

Future improvements could include hyperparameter tuning, additional model comparisons, and validation on external datasets.

---

## Author

Caroline Jose

Student


