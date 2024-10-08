SpotMyVibes
Check out the deployed application with your own spotify login!
https://spotmyvibes.onrender.com
Live App URL
Description
SpotMyVibes is a web application that helps users discover new music based on their listening habits on Spotify. With features like viewing your top tracks, recently played music, and creating custom playlists, SpotMyVibes enhances your Spotify experience with personalized music recommendations, genre-based exploration, and more. Contact me via email to get access to the spotify API for use of this application.

Features
Login with Spotify: Users can authenticate via Spotify’s OAuth2.
View Top Tracks: Shows the user's top tracks based on their Spotify listening history.
Recently Played Tracks: Displays the most recently played tracks on Spotify.
Search for Music: Search for tracks, artists, and albums directly using Spotify's API.
Create and Manage Playlists: Users can add or remove tracks from their playlists.
Music Recommendations: Get recommendations based on genre, artist, or track.
View Album and Artist Details: Explore album tracks or an artist’s top songs and albums.
User Flow
Login: The user is prompted to log in with their Spotify account.
Dashboard: After logging in, users can navigate through the app's features such as top tracks, recently played tracks, and their playlists.
Search: Users can search for specific tracks, artists, or albums.
Playlist Management: From the search results or browsing top tracks, users can add songs to their playlists.
Recommendations: Users can explore music recommendations based on different seeds (artist, track, genre).
API Used
Spotify Web API is the core API used in this app. It provides endpoints for user authentication, retrieving user profile data, top tracks, recently played tracks, playlists, and more.

Authentication: OAuth2 is used for user login and to obtain an access token.
Music Data: Endpoints are used to fetch data on tracks, albums, artists, and recommendations.
Notes: You will need a valid Spotify account to log in and access the app features. The Spotify Web API limits the number of requests and requires proper API key management for production-level usage.

Technology Stack
Backend: Python, Flask
Frontend: HTML, CSS, Jinja2 templates
Database: PostgreSQL
APIs: Spotify Web API
Authentication: Spotify OAuth2
Deployment: Heroku
Other Libraries:
Flask-WTF (Forms)
Flask-SQLAlchemy (Database ORM)
Flask-Migrate (Database migrations)
Spotipy (Spotify API integration)
Gunicorn (Production WSGI server)
