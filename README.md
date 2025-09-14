# Spotify-Track-Metadata-Analysis
Spotify Track Data Collector

# This project fetches metadata for Spotify tracks using the Spotify Web API, stores the results in a MySQL database, and visualizes the data using Python. It’s designed for data collection, analysis, and dashboarding on music metadata.
Features

    Extract track URLs and fetch details from the Spotify API

    Store track name, artist, album, popularity, and duration in MySQL

    Analyze and visualize track data with Python and pandas

    Easily extensible with SQL queries for custom insights

# Project Structure
File	Description
spotify_mysql_urls.py	Python script: pulls track data from API and inserts to MySQL
spotify.py	Python script: fetches, visualizes, and exports track metadata
spotify_track_data.csv	Example CSV output from data collection
spotify.sql	MySQL schema, example queries, and aggregations
track_urls.txt	List of Spotify track URLs to process

# Requirements

    Python 3.7+

    MySQL Server

    spotipy (pip install spotipy)

    mysql-connector-python (pip install mysql-connector-python)

    pandas, matplotlib (for visualization)
