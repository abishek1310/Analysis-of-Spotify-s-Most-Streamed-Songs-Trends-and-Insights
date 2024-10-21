
# Analysis of Spotify’s Most Streamed Songs: Trends and Insights

## Project Overview

The goal of this project is to explore and analyze the most streamed songs on Spotify, examining various attributes such as danceability, energy, and artist count to understand trends in streaming success.

## Dataset

The dataset used in this analysis is named `Spotify Most Streamed Songs.csv`, which includes the following columns:

- `artist(s)_name`: Name of the artist
- `streams`: Number of streams (in billions)
- `danceability_`: Danceability percentage
- `energy_`: Energy percentage
- `in_spotify_charts`: Indicates if the song is in Spotify charts
- `released_year`, `released_month`, `released_day`: Release date components
- `artist_count`: Number of artists contributing to the song
- `in_spotify_playlists`, `in_apple_playlists`, `in_deezer_playlists`: Presence in various playlists

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis

The analysis consists of the following steps:

1. **Data Cleaning**: 
   - Remove null values.
   - Convert date and stream columns to appropriate data types.

2. **Univariate Analysis**: 
   - Analyze distributions of streams, danceability, and energy.
   - Count the number of songs by artist count and mode.

3. **Bivariate Analysis**: 
   - Examine relationships between danceability and streams.
   - Analyze the impact of artist count on streams.
   - Identify the top artists based on total streams across platforms.

4. **Correlation Analysis**: 
   - Calculate and visualize correlations between key features.
