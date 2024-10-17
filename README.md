# Movie Recommendation System

## Overview
This project implements a movie recommendation system that suggests movies based on user input. It uses cosine similarity to compare movies based on their features, such as genres, keywords, tagline, cast, and director.

## Workflow
1. **Data Loading**: Load the movie dataset.
2. **Data Preprocessing**: Handle missing values and combine relevant features.
3. **Feature Extraction**: Convert textual data into numerical vectors using TF-IDF.
4. **Cosine Similarity Calculation**: Compute similarity scores between movies.
5. **User Input**: Take a movie name from the user and find the closest match.
6. **Recommendation Generation**: Suggest similar movies based on the similarity scores.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- difflib

## Usage
1. Place the `movies.csv` file in the project directory.
2. Run the script in a Python environment.
