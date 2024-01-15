# Spotify Top Tracks Analysis

This Python script analyzes the top tracks on Spotify. It uses the pandas, numpy, and opendatasets libraries to download, manipulate, and analyze the data.

## Data

The data is downloaded directly from Kaggle using the opendatasets library. The dataset is located at 'https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020'. After downloading, the data is loaded from a CSV file named 'spotifytoptracks.csv' located in the 'top-50-spotify-tracks-2020' directory.

## Features

The script performs the following analyses:

1. Prints the number of observations and features in the dataset.
2. Lists all the categorical and numeric features.
3. Identifies artists and albums with more than one popular track.
4. Identifies the most popular artist(s).
5. Prints the total number of unique artists and albums.
6. Lists tracks based on their danceability and loudness scores.
7. Identifies the longest and shortest tracks.
8. Identifies the most popular genre and genres with just one song in the top 50.
9. Prints the total number of unique genres.
10. Prints the correlation matrix and identifies positively and negatively correlated features.
11. Compares average scores of 'danceability', 'loudness', and 'acousticness' between different genres.

## Usage

To run the script, you need to have Python installed along with the pandas, numpy, and opendatasets libraries. You can run the script using any Python IDE or from the command line using the command 'python script_name.py', replacing 'script_name.py' with the name of the script file.

## Note

This script assumes that you have the necessary permissions to download datasets from Kaggle. If you encounter any issues while downloading the dataset, please check your Kaggle API credentials.
