# Movie Talkie : A movie recommender system made using Python and publicly available dataset.

# Data Source : 
 Data is sourced for this project from a publicly available dataset from kaggle : available [here](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset).

# Approach : 
1. A Python library called Rake is used here to extract key words from the movie description.
2. I have used the cosine similarity measure here to calculate the similarites between all the movies.
3. The calculation is done as follows : all the similarities are
    listed in a M X M matrix and we calculate the sum of similarity of every movie with every other movie. The one with the highest value is going to be the recommended movie. 