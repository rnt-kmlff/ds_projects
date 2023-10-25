# KNN And Logit Models for Accurate Heart Disease Prediction

Cardiovascular disease is the leading cause of death worldwide, accounting for 31% of all annual deaths. The goal of this analysis is to build a machine learning model to predict heart disease using the Heart Failure Prediction Dataset from Kaggle (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).

The models will be based on the KNN and logistic regression classifiers and key clinical features from the dataset. By developing an accurate predictive models, we can enable early detection and management of cardiovascular disease.

The model building process involved exploratory data analysis, data preprocessing, model training and evaluation. Key steps included handling missing values, encoding categorical variables, feature selection, hyperparameter tuning and cross-validation. Accuracy was used to evaluate model performance.

After selecting the features most correlated with the target variable, including sex, chest pain type, maximum heart rate, the slope of the peak exercise ST segment, exercise-induced angina, oldpeak (ST), tuning the hyperparameters and cross-validation, the optimized KNN model with ball-tree algorithm, l2 distance metric, 27 neighbors, and uniform weights achieved the test accuracy of 85%.

The logistic regression model with 10 backward-selected features showed comparable performance, achieving 86% test accuracy.

This level of performance demonstrates the feasibility of using machine learning for heart disease prediction based on standard clinical inputs. The models can serve as a baseline for further refinement and validation on additional datasets. With more work, the models have potential to be a useful tool for early identification of patients at high risk of cardiovascular disease.
