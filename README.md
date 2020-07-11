# Article-Recommender-System

The main motive of the project is to recommend article to the user with the help of recommender system so that correct article is recommended to the user.	

# Introduction

Recommender systems have taken a huge leap towards goal, significantly improving the user experience in the online or offline environment. There are two main approaches, content-based and collaborative filtering, both with advantages and drawbacks.This article recommender system that integrates content based, collaborative and metadata recommendations, allowing users to select the method that best suits their needs.

The first approach uses keywords in order to find similar articles, given a query or an entire document. Collaborative filtering is implemented using a P2P network in which data is distributed evenly across all peers. The last technique uses data from a semantic repository containing information about articles (e.g. title, author, domain), which can be interrogated using natural language-like queries. 


# Content based filtering : 

In this system users rate items and from that a model of user preferences against the item attributes is built . An example could be in the domain of movies. Suppose someone likes science fiction, fantasy and action movies, and doesn't like romantic movies. Overtime the algorithm can accumulate this and Figure out that the user has positive scores on genres like science fiction, fantasy and action, and lower scores for romance. The algorithm might also find out that there were some actors that user likes or dislikes. For example, the user can be a fan of movies with the actor Bruce Willis, and not a fan of Ben Stiller. Content based filtering uses this information to map user ratings against the attributes of the products- in this example movies. Our approach fits in this type of algorithm as we are tryingto build a model on user feedback of news articles. 


# Collaborative filtering : 

In collaborative filtering, user ratings of other people are used rather than attribute data to predict and recommend .Collaborative filtering builds on the idea of a user model that is a set of ratings and an item model that is a set of ratings. Combining the two models, we get a sparse matrix of ratings, some of its cells are filled and most are not. So, here there are two main tasks, one is to fill the empty cells or predict a rating and second is to choose a filled cell or recommend an item.

This project explains how to built the recommendation engine from the ground up. It will include:

1: Finding readers with similar interests

2: Topic modeling

3: Making recommendations

4: Evaluation of the recommender
