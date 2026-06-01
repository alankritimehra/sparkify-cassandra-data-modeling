

# Sparkify Data Modeling with Apache Cassandra

## Project Overview
This project builds a NoSQL database using Apache Cassandra for Sparkify, a music streaming startup.

The ETL pipeline processes event data CSV files and loads the data into Cassandra tables optimized for specific analytical queries.

## Technologies Used
- Python
- Apache Cassandra
- Jupyter Notebook
- Pandas
- CSV

## Queries Implemented

### Query 1
Find artist, song title, and song length by session_id and item_in_session.

### Query 2
Find artist, song title, and user information by user_id and session_id.

### Query 3
Find all users who listened to a specific song.

## Database Schema
- song_library_by_session
- user_activity_by_session
- users_by_song

## How to Run
1. Start Cassandra.
2. Open the notebook.
3. Run all cells sequentially.
4. Verify query results.

## Author
Alankriti Mehra
