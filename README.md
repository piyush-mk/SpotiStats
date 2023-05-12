# SpotiStats

## [For Notebook click here!](/Notebook.ipynb)

## Project Description

Data analysis project to analyze my personal streaming data from Spotify

## Tech Used
- Python
- Libraries: Pandas, Numpy, Matplotlib, Seaborn, Wordcloud, Pywaffle
- Spotify Personal Data

## Features
1. Starter Analysis
   1. Read json file and convert to dataframe
   2. Shape of dataframe
   3. Info of dataframe
   4. Sample of dataframe
   5. Count of unique artists
   6. Count of unique songs
2. Cleaning and Formatting Data
   1. Convert milliseconds to minutes
   2. hour and minute columns
   3. endTime to Play-Time
3. Exploratory Data Analysis and Visualization
   1. Define plot style
   2. Unique artists explored
   3. Top 10 artists based on Listening Time vs number of plays
    ![](/Plots/top10.png)
   4. Song track exploration
      1. Percentage of unique songs
      2. Top 10 songs based on duration played vs times played
        ![](/Plots/top10music.png)
   5. Usage Exploration
      1. Day wise usage
      2. Day wise percentage usage by hour
        ![](/Plots/daywise.png)
      3. Average usage over a day 
        ![](/Plots/avguseday.png)
      4. Average usage in a year
        ![](/Plots/avguseyear.png)

4. Playbacks Exploration
   1. Artist wise playback
      1. Playback Hours per artist
        ![](/Plots/playbackhours.png)
      2. Playback Hours per month ( was hardest to plot ~_~ )
        ![](/Plots/playbackmonth.png)
      3. Weekly Playback hours - Waffle Chart
        ![](/Plots/playbackweek.png)
5. Insights
   1. How many hours have I spent streaming on Spotify since I first signed up
      - 207 hours, 6 minutes and 46 seconds (approx) since I first signed up.
   2. How much of my year did I spend listening to Spotify?
      - 12,375 minutes that is 5.75% of the past 5 months was spent listening to Spotify.
   3. What is the average numbers of songs I played daily?
      - 59 songs played on average daily. (in the past 5 months).
   4. When were the most songs played?
      - Most songs (256) were played on 23rd December 2022.
   5. Scatter plot of Maximum number of songs played in a day
    ![](/Plots/maxsongs.png)
   6. Top 100 Artists and wordcloud
    ![](/Plots/top100artistword.png)
   7. Top 100 Tracks and wordcloud
    ![](/Plots/top100trackword.png)
6. Conclusion</br>
    Since my first sign up on Spotify, 5months ago:</br>
    - I have spent 207 hours, 6 minutes and 46 seconds (approx) since I first signed up.
    - 12,375 minutes that is 5.75% of the past 5 months was spent listening to Spotify.
    - 59 songs played on average daily. (in the past 5 months)
    - Most songs (256) were played on 23rd December 2022.
    - I have played 1816 unique songs
    - I have played music from 695 unique artists
    - On Fridays, I spent more time listening to Spotify.
    - Maximum usage is around 2pm.
    - On 23rd December 2022, I played 256 songs which is the maximum number of songs played in a day.
    - My favourite artist is Kendrick Lamar with 1098 playbacks.
    - My favourite track is 'Superhero (Heroes & Villains)' with 112 playbacks.
7. References
- [kmcd14/spotify](https://github.com/kmcd14/spotify)
- [Spotify personal data analysis using R by Joy Pham](https://medium.com/@joypham7/spotify-personal-data-analysis-858c8fbe6983)
- [Spotify Data Analysis and Visualisation with Python by Jeremy Onim](https://blog.devgenius.io/spotify-data-analysis-with-python-a727542beaa7)