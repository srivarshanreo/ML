# Movie Recommendation System

The notebook implements user-based collaborative filtering for User 2.

## Run

From the repository root, open `notebooks/user_based_collaborative_filtering.ipynb` and run the cells in order. It uses NumPy and pandas and expects these files under `data/raw/movielens/`:

- `ratings_small.csv`
- `links_small.csv`
- `movies_metadata.csv`

The recommender ranks the five nearest users by cosine similarity, considers only their ratings of at least 4.0, excludes movies User 2 has rated, and sorts the remaining movies by their mean rating.

The full `ratings.csv`, `credits.csv`, and ZIP archive are kept locally and excluded from Git; they are not required by this notebook.
