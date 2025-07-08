# Tableau Spotify Features Data Visualisation

This project explores and visualizes Spotify audio feature data using Tableau. The visualizations aim to uncover music trends, compare genres and artists, and provide insights into popular Spotify tracks through a variety of audio attributes.

## Table of Contents

- [About the Project](#about-the-project)
- [Data Source](#data-source)
- [Data Dictionary](#data-dictionary)
- [Tableau Visualisations](#tableau-visualisations)
- [Screenshots](#screenshots)
- [How to Use](#how-to-use)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

---

## About the Project

This repository contains Tableau visualizations created from a dataset of Spotify tracks, including detailed audio features for each song. The goal is to analyze and present trends in music characteristics such as popularity, danceability, energy, and more.

## Data Source

The dataset used in this project is an Excel file named `Extension_Task_SpotifyFeatures_COPY.xls` (referenced in the Tableau workbook). This file contains thousands of tracks from Spotify, each annotated with various audio features.

- **Tableau Workbook:** [`Spotify.file.twb`](https://github.com/YusafM/Tableau-Spotify-Features-Data-Visualisation/blob/main/Spotify.file.twb)

## Data Dictionary

The following columns are included in the dataset and used for visualisation:

| Column             | Type      | Description                                                        |
|--------------------|-----------|--------------------------------------------------------------------|
| genre              | string    | Genre of the track                                                 |
| artist_name        | string    | Name of the artist                                                 |
| track_name         | string    | Name of the track                                                  |
| track_id           | string    | Unique Spotify track ID                                            |
| popularity         | integer   | Popularity score (0-100)                                           |
| acousticness       | real      | Confidence measure of whether the track is acoustic (0.0-1.0)       |
| danceability       | real      | Danceability of the track (0.0-1.0)                                 |
| duration_ms        | integer   | Duration of the track in milliseconds                               |
| energy             | real      | Intensity and activity (0.0-1.0)                                    |
| instrumentalness   | string    | Predicts whether a track contains vocals                            |
| key                | string    | Key of the track (e.g., C, D#, F)                                  |
| liveness           | real      | Probability the track was performed live (0.0-1.0)                  |
| loudness           | real      | Overall loudness in decibels (dB)                                   |
| mode               | string    | Modality (major/minor)                                             |
| speechiness        | real      | Presence of spoken words (0.0-1.0)                                  |
| tempo              | real      | Tempo of the track in beats per minute (BPM)                        |
| time_signature     | date      | Time signature (e.g., 4/4, 3/4)                                     |
| valence            | real      | Musical positiveness (0.0-1.0)                                      |

## Tableau Visualisations

The Tableau workbook (`Spotify.file.twb`) connects directly to the dataset and contains multiple dashboards and sheets that visualize the above features. Example analyses include:

- Distribution of genres and popular artists
- Relationship between danceability, energy, and popularity
- Audio feature comparison across genres
- Trends in tempo, valence, and loudness

## Screenshots

Below are sample screenshots from the Tableau dashboards in this repository:

- ![Screenshot 1](https://github.com/YusafM/Tableau-Spotify-Features-Data-Visualisation/blob/main/Screenshot%202025-06-02%20151313.png)
- ![Screenshot 2](https://github.com/YusafM/Tableau-Spotify-Features-Data-Visualisation/blob/main/Screenshot%202025-06-02%20151359.png)
- ![Screenshot 3](https://github.com/YusafM/Tableau-Spotify-Features-Data-Visualisation/blob/main/Screenshot%202025-06-03%20113059.png)
- ![Screenshot 4](https://github.com/YusafM/Tableau-Spotify-Features-Data-Visualisation/blob/main/Screenshot%202025-06-03%20113438.png)

## How to Use

1. **Download the Repository**: Clone or download this repository to your local machine.
2. **Open Tableau Workbook**: Open `Spotify.file.twb` using Tableau Desktop.
3. **Connect to Data**: Ensure you have the referenced Excel file (`Extension_Task_SpotifyFeatures_COPY.xls`) available or update the data source path in Tableau to your local copy.
4. **Explore Dashboards**: Browse through the dashboards and sheets for different visualizations and insights.

## Requirements

- Tableau Desktop (compatible with version 18.1 or higher)
- The source Excel dataset (not included in the repo due to size/license)

## Acknowledgements

- Spotify for the audio feature data
- Tableau for powerful data visualization tools

---
