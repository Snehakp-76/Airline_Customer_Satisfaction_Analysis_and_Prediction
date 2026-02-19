# Airline_Customer_Satisfaction_Analysis_and_Prediction
## Problem Statement
Understanding customer satisfaction is critical for airlines to improve service quality and customer retention. This project analyzes airline customer data to identify factors influencing satisfaction and builds classification models to predict whether a customer is satisfied or not.

## Dataset Overview
- Dataset contains customer demographics, travel details, service ratings, and flight information
- Target variable: Satisfaction (Satisfied / Neutral or Unhappy)
- Data prepared from a structured CSV file

## Approach
- Loaded and cleaned the dataset by handling missing values and removing inconsistencies.
- Performed exploratory data analysis (EDA) to understand data distribution and relationships.
- Encoded categorical variables and applied feature scaling using StandardScaler.
- Trained and evaluated multiple classification models.
- Compared model performance and analyzed feature importance.

## Tools & Technologies
- Programming: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Machine Learning: Scikit-learn
- Techniques: EDA, data preprocessing, classification, model comparison, feature importance

## Model Development & Evaluation
- Implemented and compared multiple classifiers:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Models were evaluated using:
  - Accuracy
  - Precision, Recall, and F1-Score

## Key Insights
- Identified service-related features as strong indicators of customer satisfaction.
- Ensemble models demonstrated better performance in capturing complex patterns.
- Feature importance analysis highlighted key factors influencing satisfaction outcomes.

## Future Improvements
- Perform hyperparameter tuning to further improve model performance.
- Address class imbalance using resampling techniques.
- Explore model deployment and real-time prediction workflows (learning phase).

## Learnings
- Gained hands-on experience with classification-based ML workflows.
- Strengthened understanding of EDA, preprocessing, and evaluation metrics.
- Improved ability to interpret model outputs and feature importance.
