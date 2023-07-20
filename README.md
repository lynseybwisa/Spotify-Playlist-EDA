# Spotify-Playlist-EDA

Objective : In this notebook we will play around with the spotify datasets and do the following things
1. Do EDA on data to understand the size of the data
2. To reduce memory usage take each distinct Song and give it a numeric value 
3. Convert each playlist of the user into sequential data by randomly grouping them based playlist name
4. Hypothesis is simple that each song inplaylist can be played randomly

#Spotify playlists dataset
This dataset is based on the subset of users in the #nowplaying dataset who publish their #nowplaying tweets via Spotify. In principle, the dataset holds users, their playlists and the tracks contained in these playlists.

The csv-file holding the dataset contains the following columns: "user_id", "artistname", "trackname", "playlistname" , where
1. user_id is a hash of the user's Spotify user name
2. artistname is the name of the artist
3. trackname is the title of the track and
4. playlistname is the name of the playlist that contains this track.

The separator used is , each entry is enclosed by double quotes and the escape character used is .
