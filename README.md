# Item_and_User_Based_Recommendation

# Business Problem
The document starts by outlining the business problem. It asks to provide 10 film recommendations for a given user ID, using both item-based and user-based recommender methods.

# Dataset Story
The dataset used comes from MovieLens, a movie recommendation service. It contains:
- Ratings for 27,278 movies.
- A total of 20,000,263 ratings.
- Data from 138,493 users, ranging from January 9, 1995, to March 31, 2015.
- All users in the dataset have rated at least 20 movies.

# Project Tasks
The document breaks down the project into several tasks, each with specific steps:

## User Based Recommendation

### Data Preparation
- Reading movie and rating datasets.
- Merging datasets.
- Filtering out movies with less than 1000 ratings.
- Creating a pivot table.

### Identifying Movies Watched by the Target User
- Select a random user ID.
- Create a list of movies watched by this user.

### Finding Other Users Who Watched the Same Movies
- Create a new dataframe.
- Find users who have watched 60% or more of the movies watched by the target user.

### Identifying Users Similar to the Target User
- Filter and find users with a high correlation (above 0.65) with the target user.

### Calculating Weighted Average Recommendation Score
- Calculate a new variable 'weighted_rating'.
- Select and sort the top 5 recommended movies.

## Item Based Recommendation

### Recommendation Based on Last and Highest Rated Movie
- Focus on the last and highest-rated movie by the selected user.
- Recommend 5 movies based on item-based methodology.

# Conclusion
This document appears to be a comprehensive guide for building a hybrid recommender system, including detailed steps for data preparation, analysis, and the implementation of recommendation algorithms. It could be particularly useful for someone in the fields of data science or data engineering, especially with a focus on machine learning and recommendation systems.
