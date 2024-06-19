# simple-recommender-system
Simple Tutorial for Building a Simple Recommender System and a Content-Based Recommender System for Movies

In this tutorial, we will cover how to build two types of recommender systems for movies: a simple recommender system and a content-based recommender system.

1- Simple Recommender System
This system returns the top movies based on specific computed scores and recommend them to users.

Steps:

-Compute scores for each movie (based on vote average and vote count)

-Sort movies based on these scores.

-Recommend the top movies to users.

2-Content-Based Recommender System
This system returns movies that are similar to a specific movie.

Steps:

-Convert the metadata of movies into vectors to compute similarities (using TF-IDF technique).

-Compute the similarity between movies using a similarity measure (cosine similarity).

-For a given movie, recommend other movies that have high similarity scores.
