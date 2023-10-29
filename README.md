# Group-Recommender-System
We create a Collaborative filtering based Recommender System for a group of users.
# Matrix Factorization for Recommendation
Matrix factorization (MF) techniques are the core of many popular algorithms, including word embedding and topic modeling, and have become a dominant methodology within collaborative-filtering-based recommendation. MF can be used to calculate the similarity in user’s ratings or interactions to provide recommendations. In the simple user item matrix below, Ted and Carol like movies B and C. Bob likes movie B. To recommend a movie to Bob, matrix factorization calculates that users who liked B also liked C, so C is a possible recommendation for Bob.
![img-2](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/dc95ad9e-0ac7-4109-b80e-4ae52a6ec199)

![img-4](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/6339e4b8-143f-4bac-b076-292d2ae4893c)

# Matrix factorization using the  alternating least squares (ALS) algorithm
This method approximates the sparse user item rating matrix u-by-i as the product of two dense matrices, user and item factor matrices of size u × f and f × i  (where u is the number of users, i the number of items and f the number of latent features) . The factor matrices represent latent or hidden features which the algorithm tries to discover. One matrix tries to describe the latent or hidden features of each user, and one tries to describe latent properties of each movie. For each user and for each item, the ALS algorithm iteratively learns (f) numeric “factors” that represent the user or item. In each iteration, the algorithm alternatively fixes one factor matrix and optimizes for the other, and this process continues until it converges.  
![img-5](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/4117dd26-bd27-49fd-ab02-786cba18b772)
![img-6](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/93f2ed2a-81d9-4903-ad00-97b18bae05c9)



We generate groups of users of user defined size and tried to predict group ratings using methods described below.

There are numerous techniques for preference aggregation that is generally divided into three categories:
Majority-based strategies which use the most popular items for aggregation (e.g., Plurality Voting)
Consensus-based strategies where preferences of all group members are considered (e.g., Average, Average without Misery, Fairness)
Borderline strategies which only considers a subset (e.g., Dictatorship, Least Misery, Most Pleasure)



# Link to research paper on which project is based
https://www.sciencedirect.com/science/article/pii/S0020025516300196

# Dataset
https://media.geeksforgeeks.org/wp-content/uploads/Movie_Id_Titles.csv \n
https://media.geeksforgeeks.org/wp-content/uploads/file.tsv

# References 
https://www.nvidia.com/en-us/glossary/data-science/recommendation-system/
