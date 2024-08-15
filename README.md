# Movie_recommendation_system
This project is a movie recommendation system built with Streamlit and powered by a machine learning model. It recommends movies based on a selected title using cosine similarity and displays movie posters fetched from the TMDB API.

# Overview
The movie recommendation system helps users discover movies similar to their favorites. By selecting a movie from the list, users receive a list of top 10 recommended movies along with their posters. This project leverages machine learning techniques to analyze the features of movies and find similarities between them. It uses the TMDB API to fetch and display movie posters, enhancing the user experience by providing visual context for the recommendations. The system is built with Streamlit, providing an interactive and user-friendly interface for users to explore movie recommendations easily.
# Dataset
The dataset used for this project contains information about movies, including their titles and IDs. It is processed and stored in movie_data.pkl. The dataset is used to calculate the cosine similarity between movies.

# Model
The model for recommending movies is based on cosine similarity. Cosine similarity is used to measure the similarity between movie titles. The model computes the similarity scores and suggests the top 10 similar movies based on the selected movie title.

#  Results
The system provides the top 10 recommended movies for any selected movie title. It also fetches and displays the posters of these recommended movies using the TMDB API.

![sc114](https://github.com/user-attachments/assets/dc7f94d9-1978-4985-8b8f-4dba67e2a645)

