# Movie Recommendation System

This project implements a movie recommendation system using Python. The system processes data from two CSV files (`tmdb_5000_credits.csv` and `tmdb_5000_movies.csv`) containing information about movies, including credits, genres, keywords, cast, and crew. It then uses natural language processing techniques to create a content-based recommendation system.

## Setup

To run the project, make sure you have the following dependencies installed:
- numpy
- pandas
- nltk
- scikit-learn

You can install the required packages using pip:

```bash
pip install numpy pandas nltk scikit-learn
```

## Project Structure

- **data/**: Folder containing CSV files (`tmdb_5000_credits.csv` and `tmdb_5000_movies.csv`).
- **main.py**: Main script for data processing and recommendation system.
- **README.md**: Documentation file describing the project and how to use it.


## Project Details

- **Data Processing**: The project uses pandas to load and preprocess movie data from CSV files, including merging dataframes, handling missing values, and converting data formats.
- **Text Processing**: The project uses natural language processing techniques such as tokenization, stemming, and vectorization to process text data like movie overviews, genres, keywords, cast, and crew.
- **Recommendation System**: The system computes movie similarities based on text data using cosine similarity and recommends similar movies based on user input.

## References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)
