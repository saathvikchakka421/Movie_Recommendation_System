# Movie Recommendation System

This project is a simple movie recommendation system built using Python and scikit-learn.

It uses collaborative filtering with KNN and cosine similarity to suggest similar movies based on user ratings.

## Dataset
MovieLens dataset from Kaggle:
- ratings.csv
- movies.csv

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

## How It Works
1. Merges ratings and movies data
2. Creates a movie-user matrix
3. Uses KNN with cosine similarity
4. Returns similar movies for a given input

## How to Run
Upload `ratings.csv` and `movies.csv`, then run the notebook cell.

## Sample Output
Input Movie: Toy Story (1995)  
Returns 10 similar movies based on user ratings.
