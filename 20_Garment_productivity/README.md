# Harnessing Data Science to Enhance Garment Manufacturing Productivity: Insights from Decision Trees and Gradient Boosting

In the competitive landscape of garment manufacturing, team productivity is a pivotal factor that directly influences operational efficiency and business success. This project leverages machine learning to predict the productivity performance of working teams in this sector. Utilizing a comprehensive dataset encompassing 15 variables and 1197 instances, this analysis provides valuable insights into the factors that drive productivity in garment manufacturing.

Our goal is to develop a predictive model that accurately forecasts whether a team will meet or exceed its target productivity, aiding managerial decisions in optimizing workforce efficiency. To achieve this, we employed various machine learning techniques, including Decision Trees, Random Forests, and Gradient Boosting Classifiers, refined through cross-validated hyperparameter tuning. The exploration and preprocessing of the data involved outlier removal, feature engineering, and missing value imputation using a KNN imputer.

Key findings reveal that the amount of financial incentive, the standard minute value (SMV), and the team size significantly influence productivity outcomes. Intriguingly, our analysis indicates that while increasing financial incentives and team size initially boosts the likelihood of achieving productivity targets, this effect plateaus beyond a certain threshold. Conversely, a higher allocated time for a task correlates with a marginally reduced probability of meeting the target. 

With an 82% accuracy achieved by the Gradient Boosting Classifier and a notable 64% precision by the Decision Tree in predicting productivity shortfalls, our results offer actionable insights for tailoring workforce strategies. The selection of the most suitable model hinges on the specific business objectives, underscoring the importance of aligning analytical approaches with organizational goals.

---

Source of data:
https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees
