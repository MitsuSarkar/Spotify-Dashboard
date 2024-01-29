#Spotify Dashboard
This Power BI dashboard allows you to explore and analyze your Spotify listening history. It contains visualizations and insights about your top tracks, artists, albums and how your music tastes have changed over time.

#Overview
The dashboard contains the following visualizations and pages:

Track Info - Details on the currently selected track like artist, release date, acousticness, danceability, liveness, speechiness, valence, energy.
Average Streams per Year - A line chart showing your average monthly streams by year.
Energy of Songs - A heatmap showing the energy level of your top tracks.
Album Art - A grid of album covers for your top albums.
Listen History - A bar chart showing how much you've listened to each song.
Top Tracks by Streams - A table listing your top tracks and their total streams.
Tracks by Release Date - A line chart showing tracks grouped by release year.
Year in Review - A page for each year showing your top track for each month.
Data is sourced directly from the Spotify API using the spotifyr R package. The dashboard is interactive - you can filter the visuals by year, artist, album or other attributes.

#Installation
Sign up for a free Spotify developer account at developers.spotify.com
Create a Spotify API app and get your Client ID and Client Secret
Get data from spotify.csv 
If you want to make your own than you have to go to ss.py and edit you client Id and client secret 
run ss.py in cmd or vs code to generate the new csv with the url of album art
Copy spotify.csv and spotify_dashboard.pbi files to your machine
Open spotify.csv and spotify_dashboard.pbix  in Power BI and refresh data
#Usage
Open the spotify_dashboard.pbix file in Power BI Desktop. The data will automatically refresh every 30 minutes. You can filter visualizations, select items, and drill down for more details.

Contributing
Pull requests are welcome! Please feel free to submit issues or contribute enhancements.

License
MIT
