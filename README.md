# 1. Movie Recommender System

This project is a content-based movie recommendation system built using the TMDB 5000 Movies and Credits datasets. The system recommends similar movies based on the selected movie using natural language processing and cosine similarity.

## 📁 Datasets Used
- Link :- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

These datasets were merged and transformed for building the recommendation engine.

## 📌 Key Steps Performed

- ✅ Data ingestion and merging
- ✅ Feature selection and transformation
- ✅ Combined relevant text features into a new `tags` column
- ✅ Applied **tokenization**, **stemming** (PorterStemmer), and **stopwords removal**
- ✅ Converted text to vectors using `CountVectorizer`
- ✅ Computed **cosine similarity** between movies
- ✅ Recommended movies based on similarity scores

## 🛠️ Libraries Used

- `numpy`
- `pandas`
- `sklearn` (`CountVectorizer`, `cosine_similarity`)
- `nltk` (`stopwords`, `PorterStemmer`) 
