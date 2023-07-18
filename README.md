# Movie Recommendation System using Regularized SVD

This project implements a movie recommendation system using Regularized Singular Value Decomposition (SVD). The dataset used in this project is the MovieLens 100k dataset.

## Dataset

The dataset used for this project is the MovieLens 100k dataset. It is a popular benchmark dataset for recommender systems, containing movie ratings provided by users. The dataset can be obtained from the [MovieLens website](https://grouplens.org/datasets/movielens/100k/).

## Regularized SVD Algorithm

Regularized Singular Value Decomposition (SVD) is a dimensionality reduction technique commonly used in recommender systems. It decomposes the user-item rating matrix into lower-rank approximations, capturing underlying patterns and relationships. The regularization term is used to prevent overfitting and improve generalization.

The algorithm involves the following steps:
1. Normalize the data by subtracting the mean.
2. Compute the covariance matrix of the normalized data.
3. Perform SVD on the covariance matrix.
4. Apply regularization to the singular values.
5. Select the top-k components to reduce dimensionality.
6. Compute the reduced feature matrix and the item matrix.
7. Predict ratings by calculating the dot product of the user and item features.

## Implementation

The implementation of the Regularized SVD algorithm in this project utilizes the Python libraries Pandas and NumPy. The dataset is preprocessed using Pandas to handle missing values and prepare it for the algorithm. The SVD computations and predictions are performed using NumPy for efficient numerical operations.

## Requirements

The following Python libraries are required to run the code:
- Pandas
- NumPy
- MatPlotLib
- Seaborn


## References

- MovieLens dataset: [MovieLens website](https://grouplens.org/datasets/movielens/100k/)
- Ricci, F., Rokach, L., Shapira, B., & Kantor, P. B. (2015). Recommender Systems Handbook. Springer.

