# **Unsupervised Machine Learning with Python**

This repository presents my process in applying KMeans clustering to a Spotify dataset of 5.000+ songs to create musically meaningful clusters of songs (=playlists) and eventually create actual playlists in Spotify.  My notebook in the “Script” folder shares every step taken in this project.  

The primary question I sought to answer was: Can machine learning be an alternative to human-created playlists?

### Situation

The business case for this project is a small-scale startup, Moosic, which relies on experts to curate playlists for their customers.  Moosic is looking to scale up operations and is considering machine learning as an alternative to human-created playlists.  I am tasked with determining whether machine learning is a viable alternative. As a parameter, playlists created should be limited to 50-250 songs each.

In my prototype I applied KMeans clustering using Quantile Transformer as my data scaler and comparing results from limiting features through the application of PCA. 

### Conclusion
Using the file shared in the “Documentation” folder, I present a prototype and the conclusion that machine learning through the application of KMeans clustering proves to be a promising alternative for Moosic’s scaling-up objectives but that further refinements and testings should be done for optimisation.

## Files

#### Data
- 	3_spotify_5000_songs: dataset as csv file
#### Script
- 	KMeans_clustering_music_playlists_prototype: notebook for the project
#### Documentation
- 	Playlists_prototype_presentation: slides used for a 5 minute presentation on the prototype and whether or not machine learning is an alternative for creating playlists

## Using the files

- 	Simply run the notebook from start to finish to follow my process.  
- 	Caveat: codes used to save csv files into Google Drive should be updated to reference user’s own Google Drive account (otherwise error code will ensue)
- 	Enjoy the music playlist samples created and shared in the notebook!
  
## Languages and Libraries Used

- 	Python (3.12.4)
- 	Pandas (2.2.2)
- 	Numpy (1.26.4)
- 	Matplotlib (3.8.4)
- 	Seaborn (0.13.2)
- 	Plotly (5.22.0)
- 	SKLearn (1.4.2)

## Tools used

- Google Colab for notebook
- Google Drive
