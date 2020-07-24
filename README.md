# Appoaches-of-Collaborative-Filtering
CSC 575 INFORMATION RETRIEVAL - CLASS PROJECT

Recommender Systems (RSs) are becoming tools of choice that provide personalized recommendation of products and services to users. 
Collaborative Filtering (CF) is the most popular method to build a Recommender System. 
In this study we build and compare two different types of Collaborative filtering: Memory based collaborative filtering and Model based collaborative filtering.  
Memory based CF requires users’ historical preferences on a set of items, and it depends on human ratings. 
Because CF is based on historical data, the main assumption of this approach is that users who have agreed in the past tend to also agree in the future.  
In other words, users who had similar likings in the past are expected to have similar likings in the future.

Since sparsity and scalability are the two biggest challenges for the standard CF method, Matrix Factorization is also explored since it is the most advanced method. 
It decomposes the original sparse matrix to low-dimensional matrices with latent factors/features and less sparsity. 
In this study, we specifically build and analyze three different CF approaches such as: user-based CF, item-based CF and Matrix Factorization. 
We explore mean absolute error (MAE) and mean square error (MSE) of different algorithms and their running times. 
We also explore how the computational time of memory-based CF changes as a result of introducing limits such as the number of songs that two users have in common 
in order to be considered in Pearson correlation. Analogously, the same limits were explored for item-based CF.
We find out that user-based CF has the lowest MAE on both the train and the test data set, 
while Matrix Factorization provides better computational time than the memory-based approaches. 
Although Matrix factorization is harder to implement, it provides a better tradeoff between rating prediction and running time than memory-based CF.
