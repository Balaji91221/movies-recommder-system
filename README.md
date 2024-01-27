# Movie Recommendation System

This is a simple movie recommendation system built using Streamlit, pandas, and the Movie Database (TMDb) API. The recommendation system suggests five movies based on user input.

## Getting Started

### Prerequisites

Make sure you have the necessary dependencies installed:

```bash
pip install streamlit pandas requests
```

# Installation

```
git clone https://github.com/your_username/your_repository.git
cd your_repository

```
Download the required pickle files: movie_dict.pkl and similarity.pkl.
# Usage
Run the Streamlit app:
```
streamlit run app.py

```
Visit the provided URL in your browser to interact with the Movie Recommendation System.

## Functionality

- **Select a Movie:**
  - Type or select a movie from the dropdown menu.

- **Get Recommendations:**
  - Click the "Recommend" button to receive a list of five movie recommendations.

- **View Recommendations:**
  - The recommended movies and their posters will be displayed in a responsive layout.

## Code Overview

- **`fetch_poster(movie_id)`:** Fetches the poster path for a given movie ID using the TMDb API.

- **`recommend(movie)`:** Recommends five movies based on the input movie using collaborative filtering and similarity scores.

- **Loading precomputed data from pickle files:** `movie_dict.pkl` and `similarity.pkl`.

- **Streamlit UI:**
  - The title of the web app is set to "Movie Recommender System."
  - A dropdown menu allows the user to select a movie.
  - Clicking the "Recommend" button triggers the recommendation function.
  - Displaying recommended movies and their posters in a responsive layout.

## Acknowledgments

- Movie data is sourced from [TMDb](https://www.themoviedb.org/).

## Disclaimer

This app uses data from TMDb but is not endorsed or certified by TMDb.

Feel free to customize the code according to your needs and add additional features to enhance the user experience!

