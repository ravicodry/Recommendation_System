# Recommendation_System

A Recommender System refers to a system that is capable of predicting the future preference of a set of items for a user, and recommend the top items.

1. Content-based recommendation : The goal of a recommendation system is to predict the scores for unrated items of the users. The basic idea behind content filtering is that each item have some features x. For example, the movie “Love at last” is a romance movie and has a high score for feature 𝑥₁, but a low score for feature 𝑥₂.

2. Collaborative Filtering : The downside of the content filtering is that it needs the side information for each item. For example, the genres such as romance and action are the side information of video. It is very expensive to have someone watch video and add side information for every video out there and every video in the future. Moreover how can one possibly list out all the features of a video? What if one want to add a new feature? Do we want to add the new feature to all the video? Collaborative filtering solve this problem. To start with, let’s think of the opposite approach to content filtering. Namely, can we predict the features of video based on user preference parameters?


Dataset:

[Movie](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

[Books](https://www.kaggle.com/ruchi798/bookcrossing-dataset)
