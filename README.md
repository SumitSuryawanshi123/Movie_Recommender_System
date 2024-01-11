# Movie Recommender System 🍿

A content-based movie recommendation system that suggests movies based on their features and utilizes cosine similarity for comparison. In this project TMDB movie data set is used. Recommendation are made using cosine similarity, it gives similarity between two movies based on the textual content of the movies.

## Content-Based Recommendation System

Content-based recommendation systems suggest items similar to what a user has liked in the past. In this project, we use various features of movies to recommend similar ones to the user.

## Cosine Similarity

Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space. In the context of the movie recommendation system, it is used to find the similarity between two movies based on their feature vectors.

The formula for cosine similarity between vectors A and B is given by:

[![formula](https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/1_cosine-similarity.png)]

## Features Used for Prediction

- **Movie ID:** Unique identifier for each movie.
- **Title:** The title of the movie.
- **Overview:** Brief description or summary of the movie.
- **Genres:** Genres associated with the movie.
- **Keywords:** Keywords associated with the movie.
- **Cast:** List of actors and actresses in the movie.

## Libraries Used

- **Pandas**
- **NumPy**
- **NLTK (Natural Language Toolkit)**

## 🎥 Video Demo
Click the image above to watch a demo of the recommendation system.

[![recommendation Demo](https://github.com/SumitSuryawanshi123/Movie_Recommender_System/blob/main/Image%20(2).png)](https://drive.google.com/file/d/1HyeSYx3Kho-Nj6356UFMpezSPnmC_VcP/view?usp=drive_link)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-recommender.git
