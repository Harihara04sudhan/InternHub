*****Movie Recommendation System******


This is a Movie Recommendation System that combines Content-Based Filtering and Collaborative Filtering techniques to suggest movies to users based on either the genres or ratings of other users. The system is built using Python, pandas, and scikit-learn, and it leverages the MovieLens 100k dataset for training and recommendations.

Features
Content-Based Filtering
Recommends movies similar to a given movie based on their genre similarity.
Uses TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to measure similarity between movies based on their genres.
Collaborative Filtering
Suggests movies based on ratings from similar users.
Uses a user-item matrix to generate movie recommendations based on user preferences and ratings.
How it Works
Content-Based: Recommends movies based on genre similarity using vectorization techniques.
Collaborative Filtering: Recommends movies by finding users who liked the same movies and recommending movies that they rated highly.
