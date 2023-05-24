## Reservoir Characterization using Machine Learning
# Introduction
In the oil and gas industry, well log data plays a critical role in reservoir characterization. However, the increasing volume of well log data has made manual analysis and interpretation challenging. This study focuses on utilizing machine learning techniques to predict porosity and lithofacies based on gamma-ray, resistivity, density, and sonic logs. By employing different machine learning models, we aim to enhance reservoir management and decision-making processes in the oil and gas industry.

# *Project Aim*
The aim of this study is to predict porosity and lithofacies of Rock Springs Uplift (RSU) well using machine learning techniques with various models. The project involves preprocessing the data by removing outliers and filling missing values, selecting relevant features, and training machine learning models for predicting porosity, permeability, and lithofacies.

# *Results*
The results of this study showcase the potential of machine learning techniques in predicting reservoir properties using well log data. Two models were developed using the Random Forest algorithm:

*Porosity Prediction:*

The first model achieved a high accuracy score of 97% in predicting porosity using RHOB, GammaRay, Vp, and Vs as input features.
Evaluation with the Random Forest Regressor yielded a mean squared error of 1.31, mean absolute error of 0.75, and an R-squared of 0.93.
Cross-validation scores demonstrated high accuracy and reliability with a mean of 0.94.
A comparison with SVM regressors indicated that the Random Forest model outperformed with better performance metrics.

*Lithofacies Prediction:*

The second model achieved an accuracy of 85% in predicting lithofacies using the same well log data.
The Random Forest Classifier yielded an R-squared of 0.86 and a mean cross-validation score of 0.85.
The classification report showed high precision, recall, and F1 scores for all lithofacies categories, resulting in an overall accuracy of 87%.
The confusion matrix further validated the model's performance, demonstrating high accuracy in predicting various lithofacies categories.

# *Usage*
To reproduce the results or utilize the models developed in this project, follow these steps:

*Preprocess the well log data by removing outliers and filling missing values.
*Select the desired features for predicting porosity and lithofacies.
*Train the Random Forest models using the chosen features and the provided dataset.
*Evaluate the models using appropriate evaluation metrics and cross-validation techniques.
*Utilize the trained models to make predictions on new well log data.

# *Dependencies*
The following dependencies are required to run the project:

*Python 3.x,
*NumPy,
*Pandas and
*Scikit-learn.
Please ensure that you have the latest versions of these packages installed.

# *Future Improvements*
Future enhancements for this project could include:

*Exploring other machine learning algorithms to compare performance and identify the most suitable models.
*Incorporating additional well log data or geological features to improve prediction accuracy.
*Conducting a more extensive analysis of the results, such as feature importance and feature engineering techniques.
*Scaling the models for large-scale applications in the oil and gas industry.
*Feel free to contribute to this project or adapt it for your specific needs.

For any questions or suggestiom
