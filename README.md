# Music Recommendation System

The Music Recommendation System is a Python application that utilizes the Spotify API to fetch music data and provide personalized song recommendations. This system combines content-based filtering and popularity metrics to suggest tracks similar to a user's favorite songs.

## Features

- **Spotify API Integration**: Connects to Spotify to fetch playlist data, including track details and audio features.
- **Content-Based Recommendations**: Uses audio features such as danceability, energy, and loudness to recommend similar songs.
- **Hybrid Recommendations**: Combines content-based recommendations with a weighted popularity score for more relevant suggestions based on the release date.
- **Data Analysis**: Utilizes pandas for data manipulation and sklearn for machine learning techniques.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/MusicRecommendationSystem.git
   ```

2. Install the required libraries:

   ```bash
   pip install spotipy pandas scikit-learn
   ```

## Usage

1. Replace `CLIENT_ID` and `CLIENT_SECRET` in the code with your Spotify API credentials.
2. Set the `playlist_id` to your desired Spotify playlist.
3. Run the script to fetch music data and generate recommendations.

## Contact

For any questions or feedback, please contact Om Shelar at omshelar37@gmail.com.
