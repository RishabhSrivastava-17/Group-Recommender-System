# Group-Recommender-System
We create a Collaborative filtering based Recommender System for a group of users.
# Matrix Factorization for Recommendation
Matrix factorization (MF) techniques are the core of many popular algorithms, including word embedding and topic modeling, and have become a dominant methodology within collaborative-filtering-based recommendation. MF can be used to calculate the similarity in user’s ratings or interactions to provide recommendations. In the simple user item matrix below, Ted and Carol like movies B and C. Bob likes movie B. To recommend a movie to Bob, matrix factorization calculates that users who liked B also liked C, so C is a possible recommendation for Bob.
![img-2](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/dc95ad9e-0ac7-4109-b80e-4ae52a6ec199)

![img-4](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/6339e4b8-143f-4bac-b076-292d2ae4893c)

We generate groups of users of user defined size and tried to predict group ratings using methods described below.

There are numerous techniques for preference aggregation that is generally divided into three categories:
Majority-based strategies which use the most popular items for aggregation (e.g., Plurality Voting)
Consensus-based strategies where preferences of all group members are considered (e.g., Average, Average without Misery, Fairness)
Borderline strategies which only considers a subset (e.g., Dictatorship, Least Misery, Most Pleasure)



Link to research paper on which project is based
https://www.sciencedirect.com/science/article/pii/S0020025516300196

Dataset
https://media.geeksforgeeks.org/wp-content/uploads/Movie_Id_Titles.csv
https://media.geeksforgeeks.org/wp-content/uploads/file.tsv

References 
https://www.nvidia.com/en-us/glossary/data-science/recommendation-system/
