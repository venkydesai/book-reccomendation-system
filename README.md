# Book Recomendation system

Dataset - https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

## Popular-based Recommendation system

## Collaborative-based Recommendation system

1. Identify users who have rated a substantial number of books, setting a threshold of at least 200 book ratings.
2. Identify books that have been rated by a significant number of users, setting a threshold of at least 50 user ratings.
3. Create a data frame with book names as rows and users as columns, focusing on the subset of books that meet the above criteria.
4. Calculate the cosine similarity between books using the cosine_similarity function from the sklearn.metrics.pairwise library.
5. Implement a recommender system that accepts a book name as input and suggests 10 similar books based on the generated similarity scores for each book relative to others.

