# Machine Learning Projects

This repository contains two focused Jupyter notebook projects.

## Movie recommendation

**Notebook:** [`movie_recommendation.ipynb`](movie_recommendation.ipynb)

Recommends movies for User 2 using user-based collaborative filtering. It finds the five most similar users, considers movies they rated at least 4.0, excludes movies User 2 has already rated, and ranks the remaining movies by their average rating.

Required files:

- `MRS/archive/ratings_small.csv`
- `MRS/archive/links_small.csv`
- `MRS/archive/movies_metadata.csv`

## Customer segmentation

**Notebook:** [`customer_segmentation.ipynb`](customer_segmentation.ipynb)

Prepares customer data, applies K-Means clustering, and compares the resulting customer groups.

Required file:

- `majorProject/marketing_campaign.csv`

## Running the notebooks

Open either notebook in Jupyter or VS Code and run its cells from top to bottom. Install the packages used by the notebook if needed: `numpy`, `pandas`, `matplotlib`, and `scikit-learn`.

The datasets are not tracked in this repository; place them at the paths listed above before running the corresponding notebook.
