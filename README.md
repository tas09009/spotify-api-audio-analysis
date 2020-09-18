# Led-Zeppelin-Spotify-features-IN PROGRESS
Pull + analyze Led Zeppelin's music from Spotify's API

**show_album-jupyter-edit**: takes in a list of albums + album ID's (pulled from a sparate code) and spits out each song from the album + its song ID

**testingspotify**: takes in song name from "show_album-jupyter-edit" to display song features.

EXAMPLE: 
```
{'0ExiKxfY5rHBW06TcV1xXU':  {'acousticness': 0.0703,
								             'analysis_url': 'https://api.spotify.com/v1/audio-analysis/0ExiKxfY5rHBW06TcV1xXU',
									           'danceability': 0.658,
									           'duration_ms': 185587,
									           'energy': 0.695,
									           'id': '0ExiKxfY5rHBW06TcV1xXU',
									           'instrumentalness': 0,
									           'key': 0,
									           'liveness': 0.13,
									           'loudness': -5.499,
									           'mode': 1,
									           'speechiness': 0.0279,
									           'tempo': 133.949,
									           'time_signature': 4,
									           'track_href': 'https://api.spotify.com/v1/tracks/0ExiKxfY5rHBW06TcV1xXU',
									           'type': 'audio_features',
									           'uri': 'spotify:track:0ExiKxfY5rHBW06TcV1xXU',
									           'valence': 0.571}
```
