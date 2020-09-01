# Spotify Playlist Generator

Given a [Spotify](https://www.spotify.com/us/) playlist id, this will generated multiple smaller playlist with a given size

## Steps to Run
### Dependencies
1. [Create Spotify Developers Account and create a new app](https://developer.spotify.com/)
2. Export Client Id, Client Secret and Redirect URI
    * `export SPOTIPY_CLIENT_ID='your-spotify-client-id'`
    * `export SPOTIPY_CLIENT_SECRET='your-spotify-client-secret'`
    * `export SPOTIPY_REDIRECT_URI='your-app-redirect-url'`
3. Install Spotipy
    `pip install spotipy --upgrade`
### Running the application
`python main.py -p [playlist_id] -l [size_of_each_playlist]`
### You can then see the newly generated playlists with names `generated_playlist_[number]`