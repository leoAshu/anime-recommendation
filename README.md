# Anime Recommendation

This is an academic project based on Recommendation Systems for recommending Animes based on user interactions.

## Dataset

- Source: [Kaggle](https://www.kaggle.com/CooperUnion/anime-recommendations-database)
- Two CSV files:
    - anime.csv
    - ratings.csv
- The `anime.csv` file contains information about each anime title like: 
    - title
    - genre
    - type
    - episodes
    - rating (group rating/score)
- The `rating.csv` file contains user ratings for each anime title, with each row containing:
    - a user ID
    - an anime ID
    - a rating (user rating)

## Models

The following recommendation models are explored in this project:
- **Retrieval Model** - A model that retrieves a list of top K anime titles for a given user based on implicit interactions.
- **Ranking Model** - A model that predicts the rank of an anime for a given user based on their explicit interactions like ratings.
- **Multitask Model** - A model that combines the ranking and retrieval models.
- **Deep & Cross Network Model (DCN)** - A model that uses deep learning techniques to learn the interactions between users and anime titles.

## Requirements

Apart from the Python programming language and other standard packages like numpy, pandas, and others, the following key packages are required for the project:
- Tensorflow
- Tensorflow Recommenders

**To install:**

```
# tensorflow
pip install tensorflow

# tensorflow-recommenders
pip install tensorflow-recommenders
```

## Notebooks

The code for the project is divided into multiple Jupyter notebooks.
Each notebook contains code for a specific type of model along with the required data preprocessing.
- **retrieval_and_ranking_models.ipynb** - This notebook contains the code for building basic retrieval and ranking models.
- **ranking_model_using_metadata.ipynb** - This notebook contains the code for updating the ranking model to use metadata.
- **multitask_recommender_model.ipynb** - This notebook contains the code for building the multitask recommender model.
- **dcn_model.ipynb** - This notebook contains the code for building deep & cross network model.
- **main.ipynb** - This notebook contains code for all the models and compares their performance.

## Members

1. Ashutosh Ojha
2. Harisha Korapati
3. Zeba Wahab
