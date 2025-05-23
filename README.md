# Movie-Recommendation-Systems
Movie Recommendation Systems
![Logo](https://github.com/user-attachments/assets/881c8ae4-55ec-415b-8d3b-e33a11f04d9d)
Business Objectives :
All entertainment websites or online stores have millions/billions of items. It becomes challenging for the customer to select the right one. At this place, recommender systems come into the picture and help the user to find the right item by minimizing the options.

Recommendation Systems in the world of machine learning have become very popular and are a huge advantage to tech giants like Netflix, Amazon and many more to target their content to a specific audience. These recommendation engines are so strong in their predictions that they can dynamically alter the state of what the user sees on their page based on the user’s interaction with the app.

The business objective for us is:

To create a Collaborative Filtering based Movie Recommendation System
Predict the rating that a user would give to a movie that he has not yet rated
Minimize the difference between predicted and actual rating (RMSE and MAPE)
Data Collection :
The dataset has been obtained from Grouplens.


This dataset (ml-20m) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in the files genome-scores.csv, genome-tags.csv, links.csv, movies.csv, ratings.csv and tags.csv.



Modelling :
The following modelling approach was used in the project:

Loading & exploring the Movie and User ratings data
Creating User-Item Matrix, User-User and Item-Item similarity matrices for Movie Recommendations
Creating feature and applying ML models to predict the ratings for unseen movies for a user
The detailed analysis and model creation can be found in the .ipynb file.

Conclusions :
In this project, we learned the importance of Recommendation Systems, the types of recommender systems being implemented, and how to use matrix factorization to enhance a system.

We then built a movie recommendation system that considers user-user similarity, movie-movie similarity, global averages and matrix factorization. These concepts can be applied to any other user-item interactions systems.

We tried generating recommendations based on similarity matrix and Collaborative Filtering techniques.

We tried to predict the ratings for movies that the user might give based on its past rating behaviours and measure the accuracy using RMSE and MAPE error metrics.

Surely, there is huge scope of improvement and tring out different techniques and ML/DL algorithms.

