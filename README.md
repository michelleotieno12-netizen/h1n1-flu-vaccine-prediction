# h1n1-flu-vaccine-prediction
## Predicting H1N1 flu vaccine uptake using machine learning

# Project Overview
During the 2009 H1N1 pandemic, vaccination was one of the most important strategies used to reduce the spread of the virus. However, vaccination uptake varied significantly among individuals.

This project builds machine learning classification models to predict whether an individual received the H1N1 vaccine based on demographic characteristics, health behaviors, and vaccine attitudes.

The goal is to identify key factors influencing vaccination decisions and provide insights that can help public health organizations improve vaccination outreach strategies.

# Business Problem

Public health organizations need to understand why some individuals choose to vaccinate while others do not.

Understanding these patterns can help design better vaccination campaigns and improve vaccine uptake.

Key Question

Can we predict whether someone will receive the H1N1 vaccine using demographic information, health behaviors, and vaccine attitudes?

## Stakeholder
The primary stakeholders for this project include:

- Public health organizations

- Healthcare policymakers

- Medical professionals involved in vaccination campaigns

These stakeholders aim to increase vaccination rates in order to reduce the spread of infectious diseases and protect vulnerable populations.


# Key Results

Main findings from the analysis:

- Logistic Regression achieved 84% accuracy

- Doctor recommendation was the strongest predictor of vaccination

- Individuals with higher perceived H1N1 risk were more likely to vaccinate

- Healthcare workers had higher vaccination uptake


# Model Performance
## Confusion Matrix

The model correctly classified most individuals who did not receive the vaccine, but performance was slightly lower when predicting vaccinated individuals due to class imbalance.
![Confusion Matrix](images/plots/confusion_matrix.png)

## ROC Curve

The ROC curve shows that the model performs significantly better than random guessing, with an AUC score of approximately 0.83.
![ROC Curve](images/plots/roc_curve.png)

## Feature Importance

The most influential predictors include:

- Doctor recommendation

- Perceived H1N1 risk

- Vaccine effectiveness beliefs

- Concern about H1N1
![Feature Importance](images/plots/feature_importance.png)

## Models Used

Three classification models were developed and compared:

- Logistic Regression

- Decision Tree

- Random Forest

Model	                      Accuracy
Logistic Regression	          0.84
Decision Tree	              0.75
Random Forest	              0.83

Logistic Regression was selected as the final model because it provided the best balance between performance and interpretability.

# Key Insights

The analysis revealed several important patterns:

- Doctor Recommendation
Individuals advised by healthcare professionals were significantly more likely to vaccinate.

- Risk Perception
People who believed H1N1 posed a serious risk were more likely to receive the vaccine.

- Occupation
Healthcare workers showed higher vaccination rates due to increased exposure and awareness.

- Age Group
Older individuals were more likely to vaccinate than younger populations.

# Recommendations

Public health organizations could improve vaccination uptake by:

- Encouraging healthcare providers to actively recommend vaccines

- Increasing public awareness about influenza risks

- Targeting groups with lower vaccination rates

- Expanding workplace vaccination programs

# Limitations

- The dataset relies on self-reported survey data

- Data reflects 2009 pandemic conditions

- Some missing values required imputation

- Machine learning identifies patterns but does not establish causation

# Future Improvements

Future work could include:

- Testing additional models such as Gradient Boosting or XGBoost

- Applying more advanced feature engineering

- Incorporating newer vaccination datasets

- Including healthcare access and geographic variables

# Conclusion

This project demonstrates how machine learning can help identify the key factors that influence vaccination decisions. By understanding the drivers of vaccination behavior, public health organizations can design more effective campaigns that encourage individuals to protect themselves and their communities.


















































































































