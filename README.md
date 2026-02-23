# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ARYAN U S
*INTERN ID*: CTIS2401
*DOMAIN*: DATA ANALYSIS
*DURATION*: 6 WEEKS
*MENTOR*: NEELA SANTHOSH

## Machine Learning Predictive Analysis – Fitness Dataset
This project presents an end-to-end predictive analysis workflow using machine learning techniques applied to the Linnerud dataset, a lesser-known dataset available in the scikit-learn library. The primary objective of this project is to explore the relationship between physical fitness performance and physiological body measurements, and to evaluate how well exercise-related variables can predict multiple health outcomes simultaneously.

The Linnerud dataset consists of two main components. The input features represent physical exercise performance, including the number of chin-ups, sit-ups, and vertical jumps performed by individuals. The target variables represent physiological measurements, namely body weight, waist circumference, and resting pulse rate. Each observation corresponds to an individual, making this dataset suitable for analyzing how fitness activity correlates with body characteristics. Unlike commonly used benchmark datasets, Linnerud offers a more unique and realistic scenario, making it an interesting choice for demonstrating multi-output regression.

The machine learning task addressed in this project is multi-output regression, where a single model is trained to predict multiple dependent variables at once. This approach reflects real-world problems in health analytics, where multiple physiological indicators are often interconnected and influenced by shared factors. The workflow begins with data loading and exploration, followed by preprocessing steps such as feature scaling to ensure that variables with different units and ranges do not bias the model.

A Linear Regression model is used as the baseline estimator due to its interpretability and suitability for small datasets. The dataset is split into training and testing sets to evaluate the model’s ability to generalize to unseen data. Model performance is assessed using Mean Squared Error (MSE) and R² score for each target variable independently. These metrics provide insight into both prediction accuracy and the proportion of variance explained by the model.

The results reveal that exercise performance variables have stronger predictive power for waist circumference compared to body weight and pulse rate. This suggests that abdominal measurements are more directly influenced by physical activity, while body weight and pulse are affected by additional factors such as diet, genetics, and stress levels. The variation in performance across targets highlights an important insight: machine learning models may perform differently depending on the nature of the outcome variable, even when trained on the same input features.

This project demonstrates the practical strengths and limitations of predictive modeling on small, real-world datasets. While the model successfully captures meaningful relationships between fitness activity and certain physiological measures, the limited sample size restricts overall predictive accuracy. These limitations are acknowledged as part of the analysis, reinforcing the importance of data quality and quantity in machine learning applications.

Overall, this repository showcases a complete and reproducible machine learning pipeline, including data exploration, preprocessing, model training, evaluation, and interpretation. The project serves as a clear example of how machine learning techniques can be applied to health and fitness data to extract insights and support predictive analysis, making it suitable for academic submissions, portfolio projects, and introductory applied machine learning demonstrations.

# OUTPUT



