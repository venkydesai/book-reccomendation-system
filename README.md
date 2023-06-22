# Book Recomendation system

Dataset - https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

## Popular-based Recommendation system

1. Gather book ratings from users.
2. Determine the average rating for each book.
3. Apply a filter to consider only books that have been rated by at least 250 users.
4. Rank the books based on their average ratings in descending order.
5. Build a recommender system that displays the top books according to their average ratings, considering the condition of a minimum of 250 user ratings.

## Collaborative-based Recommendation system

1. Identify users who have rated a substantial number of books, setting a threshold of at least 200 book ratings.
2. Identify books that have been rated by a significant number of users, setting a threshold of at least 50 user ratings.
3. Create a data frame with book names as rows and users as columns, focusing on the subset of books that meet the above criteria.
4. Calculate the cosine similarity between books using the **cosine_similarity** function from the **sklearn.metrics.pairwise** library.
5. Implement a recommender system that accepts a book name as input and suggests 10 similar books based on the generated similarity scores for each book relative to others.

