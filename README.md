# Movie-Rec-System

This project contains two separate implementations of a movie recommendation system using collaborative filtering techniques. 
The user provides a movie name or user ID, and the system recommends similar movies based on viewing patterns.

- Files
- 
item-based.ipynb: Recommends movies similar to a given movie based on item-item similarity.

user-based.ipynb: Recommends movies based on what similar users have liked

-How Each Notebook Works

**item-based.ipynb**

Loads and merges movies.csv and ratings.csv.

Creates a pivot table (user-movie rating matrix).

Calculates cosine similarity between movies (columns).

Asks for a movie name as input.

Returns a list of movies most similar to the selected movie.

**user-based.ipynb**

Loads and merges movies.csv and ratings.csv.

Creates a pivot table (user-movie rating matrix).

Calculates cosine similarity between users (rows).

Asks for a movie name as input.

Finds users who liked the movie and recommends movies that similar users also liked.

A simple gui system is used to display the output.

-Requirements: 

  Must have python, pandas, numpy, tkinter, scikit learn. 
  
-Dataset
The code uses:
movies.csv: Contains movie titles and IDs.
ratings.csv: Contains user ratings for movies.
These files must be in the same directory as the notebook.

