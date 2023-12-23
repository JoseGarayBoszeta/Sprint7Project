# Sprint7Project
Sprint7Project - An introductory exploration of Machine Learning classification algorithms

# Project description
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.<br>
You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model.<br>
Develop a model with the **highest possible accuracy.** In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.<br>

# Project purpose:
To investigate three different basic algorithms for machine learning included on Scikit Learn: Decision Tree, Random Forest and Logistic Regression. We will divide the dataframe in three sets: training (60%) validation (20%) and testing (20%). We will train each algorithm with different hyperparameters and measure their performance with the accuracy_score, classification_report and confusion_matrix methods. This will allows us to find the best model to use for classification tasks.
