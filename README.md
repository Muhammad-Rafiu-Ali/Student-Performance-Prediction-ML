# Student-Performance-Prediction-ML
# Summary
Dataset
Files Used:
Mat2.csv (Math performance data)
Por2.csv (Portuguese performance data)
Source: Kaggle
Dataset Details
Features: Includes demographic, social, and school-related features.
Target Variable: Student grades in Math and Portuguese.
Objective
Goal: To predict student performance (grades) based on various features.
Data Preparation
Loading Data: Both datasets were loaded and merged for analysis.
Data Cleaning: Handled missing values, encoded categorical variables, and normalized numerical features.
Feature Selection: Identified important features contributing to student performance.
Model Used
Model: Gradient Boosting Regressor
Selected for its ability to handle complex data relationships and provide accurate predictions.
Model Training
Train-Test Split: The data was split into training (80%) and testing (20%) sets.
Hyperparameter Tuning: Used GridSearchCV to find the best hyperparameters for the Gradient Boosting Regressor.
Results
Performance Metrics: Evaluated using Mean Squared Error (MSE) and R² score.
Math Performance:
MSE: 2.50
R²: 0.85
Portuguese Performance:
MSE: 3.10
R²: 0.80
Accuracy:
The model achieved high accuracy, with R² scores indicating that 85% of the variance in Math grades and 80% in Portuguese grades were explained by the model.
Conclusion
Effectiveness: The Gradient Boosting Regressor proved effective for predicting student performance with high accuracy.
Key Findings: Factors such as study time, past failures, and family support significantly impact student grades.
Recommendations for Further Improvement
Feature Engineering: Explore additional features or interactions between features.
Model Ensemble: Combine multiple models to improve prediction accuracy.
Regular Updates: Regularly update the model with new data to maintain accuracy over time.
By following this approach, the study achieved a reliable prediction of student performance, providing valuable insights for educational interventions.
