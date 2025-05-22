Netlix Movie Recommender System (User-Based Collaborative Filtering)

This is a simple movie recommendation system using **User-Based Collaborative Filtering**. It uses user similarity (cosine similarity) to recommend movies that similar users have rated highly, but the target user hasn't seen yet.

Features
- Simulates a mini movie-rating dataset
- Computes user similarity matrix with cosine similarity
- Recommends top N movies a user hasn't rated
- Super beginner-friendly, readable, and hackable

How It Works
1. Data Setup: Simulated user-movie ratings using a pandas DataFrame.
2. Pivot Table: Converts the data into a user-item matrix.
3. Fill Missing Values: Missing ratings are filled with `0`s.
4. Cosine Similarity: Measures how similar users are to one another.
5. Recommendation Function: Picks movies rated by similar users that the current user hasn't seen.
