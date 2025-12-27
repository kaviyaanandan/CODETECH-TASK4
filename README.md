Name: KAVIYA

Company: COOTECH IT SOLUTIONS
ID: CT04DR2957
Domain: Machine Learning
Duration: DEC 2025 – JAN 2026
Mentor: MUZAMMIL

Overview of the Project
Project Title- Recommendation System Using Collaborative Filtering and Matrix Factorization


Objective

The objective of this project is to build a Recommendation System using Collaborative Filtering with Matrix Factorization techniques. The project utilizes Singular Value Decomposition (SVD) to predict missing user–item ratings and generate personalized recommendations.

This project helps in understanding how recommendation engines work, how latent features are learned, and how user preferences can be predicted using historical rating data.

Key Activities
· Dataset Creation and Loading

A sample dataset containing user IDs, item IDs, and ratings is created to simulate real-world user–item interactions. This dataset serves as the foundation for building the recommendation system.

· User–Item Matrix Construction

The dataset is transformed into a user–item rating matrix using pivot tables. Missing values are filled with zeros to prepare the matrix for matrix factorization.

· Matrix Factorization Using SVD

Truncated Singular Value Decomposition (TruncatedSVD) is applied to:

Reduce dimensionality

Learn latent features for users and items

Reconstruct the rating matrix with predicted values

This allows the model to estimate ratings for items that users have not yet rated.

· Rating Prediction

The reconstructed matrix provides predicted ratings for each user–item pair. These predictions are used to recommend new items to users.

· Model Evaluation

The recommendation system is evaluated using Root Mean Squared Error (RMSE) by comparing actual ratings with predicted ratings on a test dataset.

· Recommendation Generation

A recommendation function is implemented to:

Identify items not yet rated by a user

Rank items based on predicted ratings

Recommend top-N items for each user
