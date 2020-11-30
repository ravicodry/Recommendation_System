# Recommendation_System

A Recommender System refers to a system that is capable of predicting the future preference of a set of items for a user, and recommend the top items.

1. # Content-based recommendation # : The goal of a recommendation system is to predict the scores for unrated items of the users. The basic idea behind content filtering is that each item have some features x. For example, the movie “Love at last” is a romance movie and has a high score for feature 𝑥₁, but a low score for feature 𝑥₂.

2. # Collaborative Filtering # : The downside of the content filtering is that it needs the side information for each item. For example, the genres such as romance and action are the side information of movies. It is very expensive to have someone watch movies and add side information for every movie out there and every movie in the future. Moreover how can one possibly list out all the features of a movie? What if one want to add a new feature? Do we want to add the new feature to all the movies? Collaborative filtering solve this problem. To start with, let’s think of the opposite approach to content filtering. Namely, can we predict the features of movies based on user preference parameters?
