# movie_recommender_system

The system uses the tags of movies to represent them as numerical vectors. It calculates the cosine similarity between all pairs of movies based on these vectors. For a given movie, it finds the most similar movies by sorting the similarity scores. The top 5 most similar movies are recommended.
For example:
If you ask for recommendations for Movie A, it might recommend Movie B (because both have "action" in their tags) but not Movie C (because its tags are dissimilar)
