# Unsupervised Machine Learning with Python

This repository showcases my process of applying **KMeans clustering** to a Spotify dataset of over 5,000 songs. The goal was to create musically meaningful clusters of songs (i.e., playlists) and ultimately generate actual playlists on Spotify. The notebook in the “Script” folder walks through every step of this project.

The main question I aimed to answer was: **Can machine learning replace human-curated playlists?**

## Situation

For this project, I worked with **Moosic**, a small-scale startup that relies on music experts to curate playlists for their customers. Moosic is exploring machine learning as a scalable alternative to human-created playlists. My task was to determine whether machine learning could effectively replace human expertise in playlist curation, with the added constraint that each playlist should contain between 50 and 250 songs.

In the prototype, I applied **KMeans clustering**, using **Quantile Transformer** as the data scaler. I also compared the results from applying **Principal Component Analysis (PCA)** to limit the features.

## Conclusion

Based on the prototype, I concluded that machine learning using **KMeans clustering** is a promising alternative for Moosic's scaling goals. However, further refinements and testing are necessary for optimization.

## Files

### Data
- **spotify_5000_songs**: The dataset (in CSV format) containing over 5,000 songs from Spotify.

### Script
- **KMeans_clustering_music_playlists_prototype**: The notebook that walks you through the entire project, including data preprocessing, clustering, and playlist creation.

### Documentation
- **Playlists_prototype_presentation**: A slide deck used for a 5-minute presentation, summarizing the prototype and evaluating whether machine learning is a viable alternative for creating playlists.

## Using the Files

1. Save the **spotify_5000_songs** dataset to your **Google Drive** or locally.
2. Update the file links within the notebook to point to the location of your saved dataset.
   - If you're using Google Drive, ensure the links point to the correct file location. This also applies to the code blocks responsible for saving music clusters as CSV files and uploading them to Google Drive. Incorrect links may cause errors.
3. Enjoy exploring the music playlist samples created and shared in the notebook!

## Languages and Libraries Used

- **Python** (3.12.4)
- **Pandas** (2.2.2)
- **Numpy** (1.26.4)
- **Matplotlib** (3.8.4)
- **Seaborn** (0.13.2)
- **Plotly** (5.22.0)
- **SKLearn** (1.4.2)

## Tools Used

- **Google Colab**: Used for running the notebook.
- **Google Drive**: Used to store data and save output files.
