# Predicting Wildfire Impact: Overcoming Challenges in Portugal’s Forest Data

In this data science project, our objective is to predict the area affected by forest fires in the northeast region of Portugal, a notoriously challenging regression problem. We employ a linear regression framework, enhanced by feature selection and regularization methods, and compare its performance with a K-nearest neighbors (KNN) approach. Our benchmark is the naive mean predictor, serving as a baseline against which to measure improvements.

Our methodology encompasses log-transforming the response variable to mitigate heavy skewness toward zero, followed by the application of various stepwise selection techniques to optimize the feature set. Despite experimenting with advanced techniques including Lasso, Ridge regression, PCA, and KNN, our results indicate only marginal enhancements over the naive benchmark. The best performing model was obtained using forward stepwise selection applied to a second-degree polynomial transformation, which slightly surpassed the baseline metrics.

The outcome of this analysis revealed that while our most effective model exhibited a moderate reduction in error rates, with a Mean Squared Error (MSE) of 1.94 and a Mean Absolute Error (MAE) of 1.13, it represents only a nominal advancement over the naive mean predictor. This suggests the necessity for alternative modeling strategies, such as a two-step approach integrating classification and regression or exploring non-parametric models, to more robustly tackle the complexities of predicting forest fire areas.

Dataset: https://archive.ics.uci.edu/dataset/162/forest+fires
