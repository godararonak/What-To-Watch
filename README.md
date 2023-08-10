# What To Watch - Movie Recommendation System


## Description

"What To Watch" is a web-based movie recommendation system that suggests similar movies based on the user's selected movie. The system utilizes a collaborative filtering approach to provide recommendations. Users can input or select a movie, and the system will display a list of recommended movies along with their posters.

## Features

- Interactive web interface for movie recommendations.
- Collaborative filtering algorithm to suggest similar movies.
- Movie posters fetched using The Movie Database (TMDb) API.

## How to Use

1. Install the required libraries by running: pip install streamlit requests pandas
 
2. Clone this repository and navigate to the project directory.

3. Run the application: streamlit run app.py


4. Open your web browser and go to the displayed URL (usually `http://localhost:8501`).

5. Select a movie from the dropdown menu.

6. Click the "Show Recommendation" button to view recommended movies along with their posters.

## Project Structure

- `app.py`: The main application code that interacts with the user and provides movie recommendations.
- `model/movie_list.pkl`: Pickled file containing a list of movies used for recommendations.
- `model/similarity.pkl`: Pickled file containing similarity scores between movies.
- `screenshot.png`: Screenshot of the application in action.

## Data Sources

- [The Movie Database (TMDb) API](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv): Used to fetch movie posters and details.

## Author

- Ronak Godara

## Acknowledgments

This project was created for educational purposes as a demonstration of building a movie recommendation system using collaborative filtering and web development with Streamlit.



