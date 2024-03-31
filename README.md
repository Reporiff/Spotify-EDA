# Spotify Songs & Personalisation Analysis 

### Background: 
Spotify offers an extensive collection of tracks, and while this variety is a strength, there's a need to curate playlists more effectively to maintain and enhance user engagement and retention.

### The Problem:
Although Spotify's library is diverse, there is evidence of user engagement stagnating. Users seem to be seeking more personalized playlist experiences that reflect their preferences. The current challenge is to use Spotify's dataset to curate playlists that better match user tastes, which could be crucial in improving engagement and reducing churn.

### Objective:
To refine playlist curation using data-driven insights into the popularity and distribution of audio features and genres/subgenres across Spotify's music library.

### To solve the problem, the key questions we should be asking are:
- Which genres and subgenres have the highest representation in the dataset, and how does this reflect in user engagement and track popularity?
- What are the common audio feature profiles of the most popular tracks within these genres and subgenres?
- How does the diversity of genres and subgenres within playlists relate to track popularity ?

### Expected Outcomes:
- **Enhanced Curation:** Curated playlists that better reflect the distribution and popularity of genres and subgenres represented in Spotify's dataset.
- **Strategic Diversity:** Strategies that consider the relationship between genre/subgenre diversity within playlists and track popularity to potentially improve user engagement.
- **Data-Driven Personalization:** Utilizing the understanding of popular audio feature profiles to create playlists that align more closely with the prevalent listener preferences.

### Data Collection
The data comes from Spotify via the spotifyr package, designed to facilitate access to Spotify's API for personal or general metadata around songs.

Shoutout to Charlie Thompson, Josiah Parry, Donal Phipps, and Tom Wolff for creating the package, and to Kaylin Pavlik for her exploration of classifying songs by genres using audio features.

### Data Dictionary
A comprehensive list of variables included in spotify_songs.csv provides insights into track IDs, names, artists, popularity, and more, with a focus on the audio features that can help us understand user preferences and predict song success.

Please refer to the [DATA_README.md](https://github.com/Reporiff/Spotify-EDA/blob/main/DATA_README.md) for detailed descriptions of each variable, including danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, and duration.


