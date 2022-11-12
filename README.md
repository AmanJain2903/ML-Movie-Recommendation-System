# ML-Movie-Recommendation-System
It's a machine learning project on movie recommendation.

Dataset : movies.csv
Recommender : recommender.py

Libraries Used : 

NumPy : Linear Algebra library
pandas : for data reading and data pre-processing
difflib : for finding closest match to the input taken from user in case of any spelling mistakes
sklearn.featue_extraction : TfidfVectorizer -> to convert textual dataset into numeric features
sklearn.metrics.pairwise : cosine_similarity -> to find similarity among rows in the dataset
Tkinter : UI library of python


1. The dataset consists of 4803 movies along with columns like title, cast, director, overview, ratings, etc.....

2. The dataset has been first pre-processed and concerned features are extracted from the dataset
   Features extracted from daatset : 
   a. Title
   b. Genres
   c. Keywords
   d. Overview
   e. Tagline
   f. Cast
   g. Director

3. Then those selected features are converted to numeric data using TfidfVectorizer

4. Then the similarity is calculated using cosine_similarity function

5. Then the recommender function is implemented, so as to find 20 similar movies to the movie given by the user as his favourite movie 

6. UI of the application is designed using Tkinter library of python


