# Movie-Recommender-System
End to end Python project for recommending movies.

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

To measure how similar two movies are, we use the Cosine Similarity technique from scikit-learn
