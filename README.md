# Top_Instagram_Influencer-_Data_Analysis
Overview-
Cleaned & analyzed Instagram Influencer dataset.
Applied Machine Learning for insights & predictions.
Goal: Understand influencer growth, engagement, and predict popularity.

Dataset-
Source: Instagram Influencers (CSV).
Key features:
     Username, Followers, Following, Engagement Rate, Posts, Country, Category.
Cleaned version used for ML tasks.

Data Cleaning-
Removed duplicates & null values.
Converted large numbers (e.g., 2.5M → 2,500,000).
Handled outliers in Followers, Engagement Rate, Posts.
Encoded categorical columns (Country, Category).
Created new features: Followers_log, Followers/Posts ratio, etc.

Exploratory Data Analysis-
Distribution of influencers by category & country.
Engagement vs Followers analysis.
Top 10 influencers by followers.
Correlation between posts, followers & engagement.

Machine Learning-
Problem Framing: Predict influencer engagement/popularity.
Target Variable: Engagement Rate / Popularity class.
Models Used: Logistic Regression, Random Forest, XGBoost.
Steps:
  Train-Test Split.
  Feature Scaling & Encoding.
  Model Training & Tuning.
  Evaluation (Accuracy, F1-score, Confusion Matrix).

Visualizations-
Bar chart → Top 10 influencers.
Histogram → Followers distribution.
Scatter plot → Followers vs Engagement.
Heatmap → Feature correlation.
Boxplot → Engagement rate by category.

Key Insights-
Entertainment & Fashion categories dominate influencers.
High follower count ≠ high engagement rate.
Engagement rate tends to decrease as followers grow.
Country-wise differences in influencer reach.
ML models can predict influencer popularity with good accuracy.

Tech Stack-
Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
Notebook: Jupyter
Optional Dashboard: Power BI / Tableau

Future Scope-
Build influencer recommendation engine.
Apply clustering (KMeans) for influencer segmentation.
Deploy ML model with Flask/Streamlit for live predictions.
