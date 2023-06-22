# Book Recomendation system

Dataset - https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

## Popular-based Recommendation system

## Collaborative-based Recommendation system

1. First, Shortlisted users who have rated at least 200 books
2. Then found the books which have been rated by at least 50 users
3. Then found a subset of the above conditions and built a data frame with book names as rows and users as its columns.
4. Found the cosine similarity between the books using the cosine_similarity function from sklearn. metrics.pairwise library
5. Built a recommender system that took the name of the book as input and suggests 10 similar books with the help of similarity scores generated for each book with respect to other books

