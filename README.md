# Movie_recommendation
This Streamlit app is a simple movie recommendation system that allows users to select a movie from a dropdown list and receive recommendations for the top 5 similar movies.

Features

Dropdown List: Users can choose a movie from a dropdown list that contains a selection of movies.
Recommendation Display: After selecting a movie and clicking the "Show Recommendation" button, the app displays the top 5 movies that are most similar to the selected movie.

Prerequisites

Before running the app, ensure that you have the following dependencies installed:

Python 3.6 or higher
Streamlit
Pickle

Data Files

The app relies on two pickle files that contain the movie data and similarity information. Ensure that the following pickle files are present in the same directory as the app script:

movie_list.pkl: Contains the list of movies.
similarity.pkl: Contains the similarity information for movies.

License

This project is licensed under the MIT License.

Acknowledgments

The movie data and similarity information used in this app are obtained from an external source: "https://www.imdb.com/search/title/?title_type=feature&primary_language=en&ref_=adv_prv". Ensure that you have the necessary permissions and comply with the appropriate licensing terms when using the data.
