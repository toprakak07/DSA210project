Personal Listening Habits Analysis

About the Project(Motivation)
This project analyzes personal music listening habits by answering the following questions:
-> Which music genres do I listen to the most?
-> At what times of the day do I listen to music?
-> Who are my most-listened-to artists, and what are my favorite songs?
-> How have my musical tastes changed over the years?
-> Can I examine the contribution of music to my work based on what hours I listen to music during the day and what type of music I listen to?  
  (For example, if I analyze the music I listened to during my university exam preparation in 2017, can these genres help in the work I do now?)

-----------------------------------------------------------------------------------------------------------------------------

Data Source
The data will be retrieved using the Spotify API, which provides access to:
-> User's top tracks,
-> User's top artists,
-> Playback times (hourly and daily data),
-> Genres of the tracks,
-> Audio features of the tracks (e.g., danceability, energy, tempo).

Spotify API Endpoints:
-> `current_user_top_tracks` - To fetch the most-listened-to tracks.
-> `current_user_top_artists` - To fetch the most-listened-to artists.
-> `audio_features` - To retrieve detailed features of each track.
-> `recently_played` - To analyze listening history.

-----------------------------------------------------------------------------------------------------------------------------

 Project Plan

 1. Data Collection:
->Data will be retrieved using the Spotify API and processed with Python's `spotipy` library. The data will then be structured into a Pandas DataFrame for easier manipulation and analysis.

 2. Data Analysis:
-> Exploratory Data Analysis (EDA):
  -> Identify the most frequently listened-to music genres.
  -> Analyze music listening habits across different times of the day (e.g., morning, afternoon, evening).
-> Top Artists and Tracks:
  -> Determine the most-listened-to artists and tracks.
-> Historical Trends:
  -> Analyze how musical tastes have evolved over the years using time series data.

 3.Visualization:
Music listening habits will be visualized using the following techniques:
-> Bar Charts: To display the most frequently listened-to genres and artists.
-> Heatmaps: To visualize the intensity of music listening habits throughout the day.
->Line Graphs: To analyze changes in musical tastes over the years.
-> Scatter Plots: To explore the relationship between listening times and genres.

Visualization tools:
-> Matplotlib and Seaborn For customized and aesthetically pleasing graphs.
-> Pandas Visualization For quick visual checks during data analysis.

-----------------------------------------------------------------------------------------------------------------------------

Goals
-> Explore and understand personal music listening habits.
-> Analyze and visualize Spotify data.
-> Gain insights into music preferences and explore opportunities for building a recommendation system.
-> Examine how listening habits influence productivity and work.

-----------------------------------------------------------------------------------------------------------------------------

Tools and Technologies
-> Python: For data analysis and visualization.
-> Spotify API: To fetch user data.
-> Pandas: For data manipulation and cleaning.
-> Matplotlib and Seaborn: For creating insightful visualizations.

