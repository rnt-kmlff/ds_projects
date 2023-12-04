# Decoding Popularity on Hacker News: A Machine Learning Approach to Predicting Post Engagement

This project presents an analysis of post popularity on Hacker News using data from a 12-month period ending on April 2023. Our dataset encompasses over 300,000 posts, and our objective is to determine the factors that contribute to a post being classified as 'Popular', defined as receiving more than 8 reactions, which are a sum of comments and points.

To approach this binary classification problem, we initially considered a range of machine learning models. After a comprehensive evaluation process, which included assessing models such as Support Vector Machines and Gradient Boosting Trees, we selected Logistic Regression for its performance and interpretability. The model tuning was achieved through grid search techniques, focusing on optimizing the hyperparameters and the classification threshold to improve the f1 score for the 'Popular' class.

The subsequent sections will detail the methodologies applied in our exploratory data analysis, feature engineering, and model evaluation. We will also discuss the insights gained from the model coefficients, particularly in relation to the significance of words in post titles and the influence of external domains linked within these posts.

---
Source of dataset:
https://www.kaggle.com/datasets/santiagobasulto/all-hacker-news-posts-stories-askshow-hn-polls/data
