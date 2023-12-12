# What Makes an App Thrive? Analyzing Success Drivers on Google Play

In the dynamically evolving landscape of mobile applications, understanding what drives an app's success is crucial for developers and marketers alike. This project delves into the realm of Google Play, one of the largest platforms for app distribution, to uncover the determinants of app popularity. By examining approximately 10,000 apps, we aim to dissect the intricate tapestry of features that propel apps to high install counts, offering valuable insights for the app development community.

The primary objective is to identify which characteristics significantly influence an app's likelihood of surpassing the 1 million installs mark, classifying these attributes as indicators of a 'successful' app. To achieve this, we employed various machine learning classifiers, including decision trees, random forests, and gradient boosting, with a focus on a pruned decision tree model for its balance of simplicity and predictive power. The analysis hones in on factors such as app size, price, and category, leveraging partial dependence plots to interpret the influence of these features.

Our approach involved meticulous data cleaning, transformation, and exploratory analysis, followed by model training and evaluation. The pruned tree model emerged as the most effective, achieving notable accuracy and recall for the 'High' install category. Preliminary findings suggest that lower-priced and larger-sized apps have a higher success probability, and certain categories like Entertainment and Photography are more conducive to high install numbers. Conversely, categories like Family, Medical, Business, and Tools appear to have a lesser impact on achieving high install counts.

---

Source of data:

https://dq-content.s3.amazonaws.com/350/googleplaystore.csv
