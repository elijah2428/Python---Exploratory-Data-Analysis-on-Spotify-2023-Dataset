
# 🎧Spotify Top Tracks 2023 - Exploratory Data Analysis (EDA) 

### This project explores a dataset of Spotify's most-streamed songs in 2023, analyzing trends, patterns, and correlations to better understand the factors that contribute to a track's popularity.

## 🎯Project Overview
### This project uses exploratory data analysis (EDA) to examine Spotify's top tracks of 2023, sourced from Kaggle. By visualizing and analyzing key metrics, we uncover insights into trends in music, artist popularity, and track characteristics that may influence streaming success.

## 📁Dataset Information
### • Source: [Top Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)🎵
### • Content: Tracks' popularity metrics, musical attributes (tempo, danceability, etc.), release dates, and playlist/chart appearances.
### • Format: CSV file with columns for track names, streams, artists, release dates, and various musical attributes.
### • Description: This dataset contains a comprehensive list of the most famous songs of 2023 as listed on Spotify. The dataset offers a wealth of features beyond what is typically available in similar datasets. It provides insights into each song's attributes, popularity, and presence on various music platforms. The dataset includes information such as track name, artist(s) name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and various audio features.

## 📊Exploratory Data Analysis
### 🔍 Dataset Overview
#### • Load the dataset and examine its structure, including the total number of rows and columns.
#### • Review data types for each feature and check for missing values to assess data quality.
#### • This gives a clear view of the dataset’s composition and highlights any necessary data cleaning steps.
### 📈 Descriptive Statistics
#### • Calculate key statistics like mean, median, and standard deviation for the streams column to understand track popularity distribution.
#### • Explore distributions for released_year and artist_count to uncover trends or outliers in release years and collaborative tracks.
### 🌟 Top Performers
#### • Identify the top 5 most-streamed tracks to highlight the highest-performing songs.
#### • Find the 5 artists with the most tracks in the dataset, showcasing the most prolific artists of 2023.
### 📅 Temporal Trends
#### • Visualize yearly release patterns to see how track release frequency changes over time.
#### • Analyze monthly releases to detect any seasonal trends, such as months with high release concentrations.
### 🎶 Genre and Music Characteristics
#### • Investigate correlations between streams and musical attributes like BPM, danceability, and energy to see if certain attributes affect popularity.
#### • Examine relationships between pairs of musical attributes (e.g., danceability vs. energy) to understand how these characteristics interact.
### 📊 Platform Popularity
#### • Compare track counts across Spotify playlists, Spotify charts, and Apple playlists to understand platform distribution.
### 💡 Advanced Analysis
#### • Identify patterns based on tracks with similar keys or modes (Major vs. Minor).
#### • Determine if any genres or artists appear more frequently in playlists or charts.

## 💡 Recommendations
### For Artists 
#### •  They can focus on creating high-energy musics to improve their appeal to listeners as this factors correlate with higher streams based on the graphs.
### For Tracks
#### • Tracks with high danceability and energy tend to perform well, which reflects the broader trend toward upbeat music in popular playlists. This could be because such tracks resonate with listeners in social and active environments, like parties, workouts, and commutes.
## 🔧Technologies Used
### • Python: Data analysis and visualization
### • Jupyter Notebook: For running EDA interactively
### • Pandas: Data manipulation
### • Matplotlib/Seaborn: Data visualization
