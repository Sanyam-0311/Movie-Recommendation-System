# Movie-Prediction-System
Predicts top 10 movies based on user’s recommendation and choices.
# Movie Recommendation System

This is a Python code implementation of a movie recommendation system. The system uses the concept of TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to recommend movies to users based on their input.

## Overview

- The code reads movie data from a CSV file, including features like genres, keywords, taglines, cast, and director.
- It preprocesses and combines these features into a single text feature for each movie.
- Then, it converts the text data into numerical values using TF-IDF vectorization.
- It calculates the similarity between movies using cosine similarity.
- Finally, it suggests similar movies based on user input.

## Data
The code reads movie data from a CSV file named 'movies.csv'. The data includes various attributes such as genres, keywords, taglines, cast, and director. Ensure that your data is in the same format and adjust the file path accordingly.

## Usage
After running the script, you will be prompted to enter your favorite movie.
The system will find the closest match in the dataset and recommend movies based on similarity.
Results
The code will display a list of recommended movies based on the similarity score to your input.

## Credits
This code uses the following Python libraries:
- numpy
- pandas
- difflib
- matplotlib
- scikit-learn
- pandas-profiling
