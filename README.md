# NBA Player Comparer 

#### ℹ️ Description:

This project originally began as a terminal-based Python program (`project.py`) and was later developed into an interactive website using Streamlit. The website can be found at [https://nba-player-comparer.streamlit.app/website](https://nba-player-comparer.streamlit.app/website).

The purpose of the project is to allow users to compare and analyse two NBA players across a selected season and over the course of their careers. It uses the `nba_api` library to retrieve NBA data, pandas DataFrames to process and manipulate the data, and Plotly and Streamlit to create interactive visualisations.

![NBA Player Comparer](https://github.com/ihsanyasinuddin-del/NBA-Player-Comparer/blob/main/nba_comparer.gif)

#### Features:
- Select a season and enter two NBA players by entering their full names
- Upon clicking compare the program will display:
- The players's headshots, current team, height and position
- View per-game statistics for:
  - Points
  - Three-point percentage
  - Field goal percentage
  - Free-throw percentage
  - Rebounds
  - Assists
  - Steals
  - Blocks
  - Turnovers
- Deltas showing the subsequent increase or decrease from the last season
- A count of which player performed better in each category, totalling up the score and displaying it at the button

#### More Stats

Further analysis can be seen on the **More Stats** page with:
- Line graphs across active seasons for: points, assists, FG%, 3pt%, and rebounds allowing comparison with a line for each player
- A radar chart using a percentile system for each category to compare the "well-roundedness" of players and strengths and weaknesses
- An interactive scatterplow allowing the user to choose the x-axis and y-axis to investigate any trends or correlation between two statistics

#### Technologies Used

- Python
- Streamlit
- pandas
- Plotly
- nba_api
