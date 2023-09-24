# Yelp Businesses 

![](Pres_first_page.png)

This is a project affiliated with the University of Chicago's Applied Data Science Program. The objective was to create two PySpark-based machine learning solutions on Google Cloud Platform (GCP). These solutions are as follows:

- Sentiment Analysis Model: This model was developed to improve restaurant services by extracting insights from unlabeled short reviews (tips). It focuses on analyzing sentiment within these reviews.
- Personalized Recommender System: The second solution is a personalized recommender system, incorporating two distinct algorithms. One algorithm recommends top users for restaurants, while the other suggests top restaurants to users.

The project involved the following key steps:


some preparation process, including, first, Use Kaggle API to Download Yelp-dataset to GCP buckets and then import data and sample some data to first run the data. 

Conducted exploratory data analysis (EDA) using BigQuery and Spark SQL on a substantial 5GB Yelp JSON dataset. This analysis yielded valuable insights spanning multiple dimensions, including business, reviews, users, and tips.

Leveraged sentiment analysis through the utilization of Natural Language Processing (NLP) pipelines and classification models. These models were employed to predict sentiment polarity in tip text data, utilizing a trained dataset containing 4.72 million Yelp reviews. Notably, an accuracy rate of 0.8978 was achieved with the LinearSVC model following comprehensive model comparisons and hyperparameter tuning.

Developed a Collaborative Filtering recommender system using PySpark ALS (Alternating Least Squares). After meticulous hyperparameter tuning, the system achieved an impressive Root Mean Square Error (RMSE) of 0.47. Furthermore, an evaluation was conducted to assess the alignment between the category word clouds of the top 10 recommendations and users' preferences based on their past visits, confirming positive validation alongside the RMSE assessment.



- Aimed to develop PySpark-based machine leaning solutions on Google Cloud Platform (GCP), covering a sentiment analysis model to improve restaurant services by understanding unlabeled short reviews (tips) and a personalized recommender system, the system includes two separate algorithms to recommend top users for restaurants and top restaurants for users
- Conducted exploratory data analysis (EDA) using BigQuery and Spark SQL on a 5GB yelp Json dataset, revealing valuable insights across business, reviews, users, and tips
- Leveraged sentiment analysis using NLP pipelines and classification models to predict sentiment polarity in tip text data based on a trained dataset of 4.72M Yelp reviews. Achieved an accuracy of 0.8978 with LinearSVC after comparing various models and performing hyperparameter tuning
- Bulit a Collaborative Filtering recommender system with PySpark ALS, achieving an RMSE of 0.47 after hyperparameter tuning. Evaluated alignment between Top 10 Recommendations' category word clouds and users' past visits preferences, affirming positive validation alongside RMSE assessment

This is a project by Yun Xing ([yxing3@uchicago.edu](mailto:yxing3@uchicago.edu)), Xiran Li ([xiranli16@uchicago.edu](mailto:xiranli16@uchicago.edu)), and Sam Ding ([zding1@uchicago.edu](mailto:zding1@uchicago.edu)). 
Feel free to reach out to them if you have any questions about the project.
