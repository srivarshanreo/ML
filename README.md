# Machine Learning Projects

This repository is organized by project and subject—not by internship or pull request.

## Projects

| Project | Contents |
|---|---|
| `projects/movie_recommendation_system/` | User-based collaborative filtering and MovieLens data |
| `projects/retail_analytics/` | Customer segmentation and Rossmann sales analysis |
| `projects/unsupervised_learning/` | Netflix stock-analysis notebook and its input data |
| `projects/home_credit_default_risk/` | Home Credit competition data |
| `projects/learning_lab/` | Standalone experiments |

Within each project, notebooks, raw data, scripts, and documents are separated by purpose. Raw data is further grouped by dataset.

## Movie recommender

Open `projects/movie_recommendation_system/notebooks/user_based_collaborative_filtering.ipynb` from the repository root and run the cells in order. The notebook reads the MovieLens files from `projects/movie_recommendation_system/data/raw/movielens/`.

For User 2, it finds the five most similar users, collects their ratings of 4.0 or higher, removes films User 2 has already rated, averages the remaining ratings per film, and displays the top 20 recommendations with titles.

## Data policy

Large raw datasets and ZIP archives stay local and are excluded from Git to keep the repository within hosting limits. The relevant local-only paths are listed in `.gitignore`.
