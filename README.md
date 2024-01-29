# Spotify Dashboard

This Power BI dashboard allows you to explore and analyze your Spotify listening history. It contains visualizations and insights about your top tracks, artists, albums and how your music tastes have changed over time.

# Overview

The dashboard contains the following visualizations and pages:
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/be78ba48-92d2-4fc9-9515-3ee6a1851823)


Track Info - Details on the currently selected track like artist, release date, acousticness, danceability, liveness, speechiness, valence, energy.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/6669a877-1917-4ab6-ae9e-86286e35b3b9)
Average Streams per Year - A line chart showing your average monthly streams by year.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/318621b1-924e-43d9-848e-85b82e6be4ba)

Energy of Songs - A heatmap showing the energy level of your top tracks.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/0e812e5a-8ce3-4907-b2fe-7a26d2f538ed)

Album Art - A grid of album covers for your top albums.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/e20b4d18-3b54-4ebd-8b0e-6c6a747c2018)

Listen History - A bar chart showing how much you've listened to each song.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/0c7e41af-e3bf-4b86-a4c5-fb19d2f47ab0)

Top Tracks by Streams - A table listing your top tracks and their total streams.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/a74435d2-826f-45d6-ba33-305b340b3350)

Tracks by Release Date - A line chart showing tracks grouped by release year.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/891e32be-3e75-4780-b57b-72418459864a)

Year in Review - A page for each year showing your top track for each month.
![image](https://github.com/MitsuSarkar/Spotify-Dashboard/assets/137225605/cebc9572-c8af-4032-af67-c14a9f4cc308)

Data is sourced directly from the Spotify API using python. The dashboard is interactive - you can filter the visuals by year, artist, album or other attributes.
There is a reset button also to reset to main page.

# Installation

Sign up for a free Spotify developer account at developers.spotify.com
Create a Spotify API app and get your Client ID and Client Secret
Get data from spotify.csv 
If you want to make your own than you have to go to ss.py and edit you client Id and client secret 
run ss.py in cmd or vs code to generate the new csv with the url of album art
Copy spotify.csv and spotify_dashboard.pbi files to your machine
Open spotify.csv and spotify_dashboard.pbix  in Power BI and refresh data

# Usage

Open the spotify_dashboard.pbix file in Power BI Desktop. The data will automatically refresh every 30 minutes. You can filter visualizations, select items, and drill down for more details.

# Contributing

Pull requests are welcome! Please feel free to submit issues or contribute enhancements.

# License
MIT
