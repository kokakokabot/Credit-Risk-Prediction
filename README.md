# Credit Risk Model Analysis

#### Overview

This project involved developing and evaluating a credit risk model using a dataset of loan applications. The goal was to predict loan defaults, a critical task for financial institutions aiming to minimize risk while providing loans to eligible applicants. We focused on using machine learning models to assess the likelihood of borrowers defaulting on their loans based on various features, including personal income, employment length, loan amount, and credit history.

#### Methodology

The analysis followed a structured approach, starting with data cleaning to handle missing values and outliers, followed by feature engineering, where categorical variables were encoded. The dataset was then split into training and testing sets for model development and evaluation.

###### Model Evaluated

- Random Forest Classifier: Selected for its ability to handle non-linear relationships and its robustness to overfitting.

###### Evaluation Metrics

The model was evaluated based on accuracy, ROC AUC score, and F1 score to assess its performance comprehensively.


#### Results

The key performance indicators for the Random Forest model were as follows:

- Accuracy: 92.93%
- ROC AUC Score: 93.38%
- F1 Score: 81.91%

These results indicate the Random Forest model's strong predictive power and its ability to distinguish between defaulting and non-defaulting loans effectively.

#### Interpretation and Recommendations

- Confusion Matrix: Recommended for a detailed breakdown of the model's performance, highlighting its ability to correctly identify defaults and non-defaults.
- Feature Importance: Suggested to understand the most significant predictors of loan default, providing valuable insights for risk management and decision-making.

#### Conclusion

The analysis demonstrated the effectiveness of using a Random Forest Classifier for credit risk assessment. Its high performance suggests it is a reliable tool for financial institutions to predict loan defaults, enabling them to make more informed lending decisions. Future work could explore further model tuning, the inclusion of additional features, and the application of alternative machine learning algorithms to enhance predictive accuracy.

#### Acknowledgments

This project was conducted using Python and libraries such as Pandas, Scikit-learn, Matplotlib, and Seaborn for data manipulation, model training, and visualization. The insights gained from this analysis are intended to support financial institutions in managing credit risk more effectively.