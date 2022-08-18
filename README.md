# Python Machine Learning: Generating Spotify Playlists
This project is a part of the [DataScience Bootcamp](https://www.wbscodingschool.com/data-science-bootcamp/) at [WBS Coding School](https://www.wbscodingschool.com/).  Other datascience projects can be found at the [main GitHub repo](https://github.com/simonmayer90).

#### Project Status: Completed

## Project Intro/Objective
The purpose of this project is to generate some Spotify playlists out of ~5000 songs using Spotify's Audio Features and machine learning methods (especially KMeans).
The questions to answer were:
- Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria?
- Is K-Means a good method to create playlists?

### Methods Used
* Data Cleaning & Transformation (using MinMaxScaler)
* Data Clustering (using KMeans) and finding a good number of clusters (using elbow and inertia method)  
* Distance Calculation: Finding the best 30 songs for each cluster (according to the eucledian distance)
* Spotify API: Inserting these 30 songs into a Spotify playlist
