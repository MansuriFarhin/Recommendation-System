# Recommendation-System

This project implements a collaborative filtering movie recommender using the MovieLens 25M dataset.

## What it does
- Finds similar movies based on user rating patterns  
- Recommends movies to a specific user using k-Nearest Neighbors (k-NN)

## Dataset
- MovieLens 25M  
- Uses `ratings.csv` and `movies.csv`

## Approach
- Filtered to movies with ≥ 1000 ratings  
- Built user–movie and movie–user rating matrices  
- Used cosine similarity for:
  - item–item similarity  
  - user–user similarity (k-NN)  
- Recommendations are based on weighted neighbor ratings

## Tech Stack
- Python  
- pandas  
- numpy  
- scikit-learn  

## Output
- Top-N similar movies for a given title  
- Top-N recommended movies for a given user  
