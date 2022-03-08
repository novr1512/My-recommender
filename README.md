# smart movie recommender

How many times did you give up movie night because you didn’t find a movie to watch?
How hard is it to find the perfect movie?
Ironically, the time consumed in searching for the right movie exceeds the movie duration.

### About the project
This project aims to solve this problem by recommending movies to users based on other users' ratings and tag similarity.
The project is based on 2 types of rocommendation types:Collabrative and content - based models 

### About the Data
This dataset (ml-25m) describes 5-star rating from MovieLens. It contains 25000095 ratings and 1093360 tag applications across 62423 movies. These data were created by 162541 users between January 9, 1995 and November 21, 2019.

The dataset contains 4 files, which are :
- movies 
- ratings
- genome-tags
- genome-scores

movies file contain info about 62423 movies,
- movieId : unique identifer across files
- title : movie title
- genres : pipe-separated list of movie genres

ratings file contain info about 25000095 ratings,
- movieId : movie unique identifer across files
- userId : user unique identifer across files
- rating : user rating out of 5 stars

tags are distrbuted in 2 files:
- genome-tags : which includes the tags id and the tag name
- genome-scores : which includes the tage id, the movie id and the relevance between them (at scale from 0 to 1)

current dataset recource is [here](https://grouplens.org/datasets/movielens/25m/)

References :
- [Alternating Least Square for Implicit Dataset with code | by Himanshu Kriplani | Towards Data Science](https://towardsdatascience.com/alternating-least-square-for-implicit-dataset-with-code-8e7999277f4b)
- [RECOMMENDER SYSTEMS: A GLOBAL OVERVIEW | by Cyrine Hlioui | fifty-five | Data Science | Medium](https://medium.com/fifty-five-data-science/recommender-systems-a-global-overview-c3a7370b3355)
- [Overview of Text Similarity Metrics in Python | by Sanket Gupta | Towards Data Science](https://towardsdatascience.com/overview-of-text-similarity-metrics-3397c4601f50#:~:text=Differences%20between%20Jaccard%20Similarity%20and,term%20frequency%20or%20tf%2Didf))
- [User Guide — pandas 1.4.1 documentation (pydata.org)](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html)
- [Implicit — Implicit 0.4.8 documentation](https://implicit.readthedocs.io/en/latest/quickstart.html)
- [recmetrics/example.ipynb at master · statisticianinstilettos/recmetrics (github.com)](https://github.com/statisticianinstilettos/recmetrics/blob/master/example.ipynb)
- [Metrics/Python/ml_metrics at master · benhamner/Metrics (github.com)](https://github.com/benhamner/Metrics/tree/master/Python/ml_metrics)

looking for to get more data from:
- https://www.imdb.com/interfaces/
- https://datasets.imdbws.com/
