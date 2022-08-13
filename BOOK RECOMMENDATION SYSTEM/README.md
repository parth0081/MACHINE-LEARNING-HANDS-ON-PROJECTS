### INTRODUCTION

During the last few decades, with the rise of Youtube, Amazon, Netflix and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

Businesses use recommender systems to recommend products and services that the customer is most likely to purchase and generate more sales and maximize profits. It has been observed in a lot of businesses like Amazon, Netflix, Flipkart and other Ecommerce websites that a big percentage of revenue they generate is from the sales of the products and services recommended to the customers by the designed recommender system. Hence a good recommendation system is very important for any business selling products/services online.


#### There are different types of Recommendation Systems:

- Content Based Recommendation System - Content-based filtering uses item features to recommend other items similar to items the user likes, based on their purchase history and ratings given to items. It gives weight to each feature based on the items user has rated and these weights are then multiplied with Item features of every item to get the likeable items for the user rankwise.

- Collaborative Filtering based Recommendation System

a) User based Collaborative Filtering- In this method the Users similarity with all other users is determined using some similarity measure like Euclidean distance/Pearson Correlation/Cosine Similarity based on the common items they have rated. Then rating for every product/service user has not purchased is determined by taking weighted average of ratings by other users and taking similarity scores as weights. Top rated items are recommended to the user.

b) Item based Collaborative Filtering- In this method similar items build neighbourhoods on the behavior of users. For example a particular user who likes a set of items then all those items are considered similar. In this way similarity of each item with every other item on the business' website is determined based on Users' ratings pattern. This method is not based on the features/contents of the items. Similarity scores of items with other items is calculated using some similarity score measure like Euclidean distance/Pearson Correlation/Cosine Similarity.

- Hybrid Recommendation System- Both collaborative and content based recommendation systems have their advantages and disadvantages. To overcome the disadvantages of both the systems most of the businesses use Hybrid recommendation system on their website or app. It is a combination of both the methods with each method having certain weightage which is determined by evaluating recommendations by keeping different weights to both methods. Hybrid recommendation systems help businesses make improved and more accurate recommendations.

In this Book recommendation system Item based Collaborative Filtering method is used for recommending similar books to the book being searched to a user. In this method similarity of each book with every other book is determined by cosine similarity measure based on the Users' ratings pattern on all the books. Each book is considered a vector with ratings (interest of every user) as its coordinates and its cosine similarity with other books is calculated. These similarity scores of each book with every other book are stored in a matrix and when a book is being searched a select number of books with highest similarity scores to searched book are recommended rankwise.

#### NOTE--> In this project since the data is too large, so I have taken: those books which had been rated by 50 users and also those users who have rated on at least 200 books.
