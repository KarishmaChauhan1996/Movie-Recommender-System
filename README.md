# Movie-Recommender-System

The Movie Recommender System is designed to help users discover movies they are likely to enjoy.
It uses machine learning models and data analysis techniques to predict user preferences based on past ratings, movie genres, keywords, and more.

## Features
Content-Based Recommendation focuses on suggesting movies that are similar in content to the ones a user already likes.

Each movie is represented by its attributes such as:

- Genres (e.g., Action, Drama, Comedy)
- Description/Overview (plot summaries)
- Tags/Keywords (e.g., space travel, romantic comedy, dystopia)
- Cast and Crew (optional)

We transform these textual features into numerical vectors using methods like TF-IDF Vectorization or Count Vectorization.

To measure how similar two movies are, we use the Cosine Similarity technique from scikit-learn.

### Steps
- Import cosine_similarity from scikit-learn
- Calculate Similarity Matrix: After vectorizing the movie features (stored in vector), we compute pairwise similarities.
- Find Movie Index: To recommend movies similar to a specific movie, we first find its index in the dataset.
- Define Recommendation Function: We create a recommend() function that:

Takes the movie title as input

Finds its corresponding index

Retrieves similarity scores with all other movies

Sorts the movies by similarity in descending order

Prints the top 5 similar movie title


