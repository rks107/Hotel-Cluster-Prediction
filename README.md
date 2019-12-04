# Hotel-Recommender-System
Hotel Recommender System Using Collaborative Filtering


This project aims to build a recommender system to predict which hotel a browsing user will click on next. Browsing history of website users' hotel interests, user's gender, geographic location, and star rating of the hotel is provided. 

First attempt uses a k-means clustering model for the prediction that groups users with similar hotel views in the same cluster. The hotel views were vectorized into binary values that represent which hotels were viewed and cluster accordingly. However, some exploratory data analysis showed that user viewing behavior is more continuous than discrete. In other words, an individual's hotel views don't fall nicely into distinct buckets.
