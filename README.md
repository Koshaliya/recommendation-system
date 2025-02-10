# Movie Recommendation System

This project is a simple movie recommendation system built using Python. 
It recommends movies based on the similarity of their overviews and genres. 
The system uses the Bag of Words technique and Cosine Similarity to find similar movies.

Features
* Dataset: The dataset contains 10,000 movies with details like title, overview, and genre.
* Recommendation: The system recommends 5 movies similar to the one you input.
* Techniques Used:
  1. Bag of Words: Converts text data into numerical vectors.
  2. Cosine Similarity: Measures the similarity between movies based on their overviews and genres.

How It Works
1. Data Preprocessing:
  The dataset is loaded and cleaned.
  The overview and genre columns are combined into a single tags column.
  Stopwords are removed, and text is converted to lowercase.

2. Vectorization: The tags column is converted into numerical vectors using CountVectorizer.

3. Similarity Calculation: Cosine Similarity is used to calculate the similarity between movies.

4. Recommendation: Given a movie title, the system finds the top 5 most similar movies based on the calculated similarity scores.
