A *recommender system* is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. They are primarily used in commercial applications.

#### Mainly three types of recommendation systems in machine learning based on filtering are used to suggest product and services to the consumers.¶

a) Content Filtering- These recommendation systems suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

b) Collaborative Filtering- Here, we try to search for look alike customers and offer products based on what his/her lookalike has chosen.This algorithm is very effective but takes a lot of time and resources.

c) Hybrid Filtering- Both Content Filtering & Collaborative Filtering is used for the purpose. you-tube uses this algorithm for their strong recommendation system.

This project is based on Content Based Filtering on TMDB dataset of 5000 movies having columns like overview, cast, crew, keyword, genres, etc.
