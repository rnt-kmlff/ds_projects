# KNN Model for Accurate Heart Disease Prediction

Cardiovascular disease is the leading cause of death worldwide, accounting for 31% of all annual deaths. The goal of this analysis is to build a machine learning model to predict heart disease using the Heart Failure Prediction Dataset from Kaggle. The model will be based on the KNN classifier and key clinical features from the dataset. By developing an accurate predictive model, we can enable early detection and management of cardiovascular disease.

The model building process involved exploratory data analysis, data preprocessing, model training and evaluation. Key steps included handling missing values, encoding categorical variables, feature selection, hyperparameter tuning and cross-validation. Accuracy was used to evaluate model performance. 

After selecting the features most correlated with the target variable, including sex, chest pain type, maximum heart rate, the slope of the peak exercise ST segment, exercise-induced angina, oldpeak (ST), tuning the hyperparameters and cross-validation, the optimized KNN model with ball-tree algorithm, euclidean distance metric, 25 neighbors, and uniform weights achieved an accuracy of 84% on the test set.

This level of performance demonstrates the feasibility of using machine learning for heart disease prediction based on standard clinical inputs. The model can serve as a baseline for further refinement and validation on additional datasets. With more work, the model has potential to be a useful tool for early identification of patients at high risk of cardiovascular disease.
