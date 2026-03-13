# Spotify Music Recommendation System

## Overview
This project builds a **Music Recommendation System** using a **Content-Based Filtering** approach with **Cosine Similarity**. The system recommends songs based on similarities in audio features such as danceability, energy, loudness, tempo, and valence.

The dataset used in this project is the **Spotify Tracks Dataset**, which contains songs from multiple genres along with various audio features representing the musical characteristics of each track.

## Features
- Song recommendation based on audio feature similarity
- Recommendation by genre
- Recommendation by artist
- Display of most popular songs
- Mood-based recommendation using audio features

## Method
The recommendation system is built using:

- Content-Based Filtering
- Cosine Similarity
- Feature Scaling (StandardScaler)

Audio features used in the model:
- danceability
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo

## Project Workflow
1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Scaling
5. Recommendation Model using Cosine Similarity
6. Advanced Recommendation Features

## Dataset
Spotify Tracks Dataset  
https://www.kaggle.com/datasets/maharshipandya/spotify-tracks-dataset

## Result
The system is able to recommend songs that have similar musical characteristics to the selected track based on audio feature similarity.
