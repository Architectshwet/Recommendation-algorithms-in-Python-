# Recommendation-algorithms-in-Python-
A project about implementation of content based, memory &amp; model based collaborative and deep learning models for bulding Recommendation engine

Designed a content-based recommendation model based on movie genres using TfidfVectorizer function from scikit-learn and applied cosine similarity
to calculate a numeric quantity that denotes the similarity between two movies.

Designed a memory based collaborative model based on user ratings and used Pearson Similarity to find the similarity/correlation between users
and movies and then used it for recommendation.

Also designed a model based collaborative model based on latent features from a low rank matrix factorization method called SVD. As it captures the underlying features driving the raw data, 
it can scale significantly better to massive datasets as well as make better recommendations based on user's tastes.

Also implemented matrix factorization for collaborative filtering expressed as a Keras Sequential model which we further used as a deep learning 
model to train to find the recommendations
