# Decoding Medical Bills: A Predictive Model for Individual Health Expenses

In this analysis, our primary objective is to understand the relationship between individual characteristics and their total medical costs, utilizing the Medical Cost Data Set from Kaggle. The dataset provides insights into the medical bills of individuals, accompanied by various demographic and personal attributes. Our goal is to develop a predictive model that accurately estimates medical costs based on these characteristics, aiding hospitals in revenue prediction and procedural planning.

We adopted a systematic approach beginning with an exploratory analysis to identify the most influential variables correlating with medical costs. Focusing on age, BMI, and smoking status, we employed a linear regression model to decipher their impacts on medical expenses. Initial residual analysis indicated signs of non-randomness, prompting the integration of second-degree polynomial features to enhance the model’s performance and accuracy.

The refined polynomial model demonstrated a marked reduction in heteroscedasticity and non-linearity, resulting in more reliable and consistent predictions. Evaluation on the test data yielded an R-squared value of 0.76, indicative of a robust model capturing a significant portion of the variance in medical costs. The RMSE of USD 5,700 further underscores the model’s precision in predicting individual medical costs, offering a valuable tool for healthcare financial planning and resource allocation.