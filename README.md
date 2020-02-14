# **Analysis of Top 50 Spotify Songs of 2019**
This repository contains analytical code, findings, and charts based off of Spotify Top 50 Songs for 2019. Specifically, this repository processes and analyzes Spotify's data by standing, genre, artist name, and song metrics.

## About the data
The analyses in this repository use data from Kaggle (https://www.kaggle.com/leonardopena/top50spotify2019)

Song Metrics:
* Beats.Per.Minute
* Energy
* Danceability
* Loudness..dB..
* Liveness
* Valence.
* Length.
* Acousticness..
* Speechiness.
* Popularity

## Data Files
Contains 
* `top50.csv` : The default download from Kaggle. Contains 2019 data for Top 50 Spotify songs by standing, genre, artist name, and song metrics.

## Analysis
The analyses were conducted in Jupyter Notebooks, using Python programming language.
* `Top_50_Spotify_2019_v2.ipynb` : Reads the `top50.csv` to produce Min/Max/Mean statistics, pie charts, scatter matrix, distribution plots, correlation heatmap, regression plots, and dependance plots.
