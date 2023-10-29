# Group Recommender System

## Overview

In this project, we implement a Group Recommender System based on matrix factorization techniques, using the Alternating Least Squares (ALS) algorithm. The system aims to provide recommendations for groups of users, considering their collective preferences.

## Matrix Factorization for Recommendation

Matrix factorization is the core methodology used in collaborative filtering-based recommendation systems. It involves breaking down the user-item interaction matrix into user and item factor matrices, revealing latent features. Recommendations are then made based on these latent features.

### Matrix Factorization using ALS Algorithm

We utilize the Alternating Least Squares (ALS) algorithm to factorize the user-item rating matrix. ALS iteratively learns latent factors for users and items by optimizing one factor matrix while fixing the other. The process continues until convergence.

## Preference Aggregation

This project involves generating groups of users with user-defined sizes and predicting group ratings. We consider various techniques for preference aggregation:

- Majority-based strategies (e.g., Plurality Voting) that use the most popular items for aggregation.
- Consensus-based strategies (e.g., Average, Average without Misery, Fairness) that take into account the preferences of all group members.
- Borderline strategies (e.g., Dictatorship, Least Misery, Most Pleasure) that only consider a subset of preferences.

## Research Paper

The project is based on the research paper available at [this link](https://www.sciencedirect.com/science/article/pii/S0020025516300196).

## Dataset

We used the following dataset files for our project:

- [Movie_Id_Titles.csv](https://media.geeksforgeeks.org/wp-content/uploads/Movie_Id_Titles.csv)
- [file.tsv](https://media.geeksforgeeks.org/wp-content/uploads/file.tsv)

## References

- [NVIDIA Data Science Glossary - Recommendation System](https://www.nvidia.com/en-us/glossary/data-science/recommendation-system/)

## How to Run

Include instructions for running your system or provide links to relevant code repositories or files.

## Contributors

- [Your Name](https://github.com/yourusername) - Role
- [Contributor Name](https://github.com/contributorusername) - Role

## License

This project is licensed under the [License Name](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Mention any acknowledgments or gratitude for tools, libraries, or other resources used in your project.
