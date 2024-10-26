# Top Spotify Songs of 2023
<img src="" width="300">

This project performs exploratory data analysis on the arrest dataset from the NYPD from 2006 - 2023, dataset from [Kaggle.](link)

- Tools used: Jupyter Notebook, Python P(andas, Numpy, Matplotlib, Seaborn)
- [Link to the full notebook](https://github.com/kennyhj/spotify2023/blob/main/spotify_notebook.ipynb)

## 1. Examining the data structure using pandas
- examining shape, data types
<img src="data header" width="750">

## 2. Cleaning
- Created a table with specifications based on what I observed in the csv file
- Dropped unneeded columns
- Cleaned null values (opted to not drop those rows outright)
- Observed values in each column to clean/group values (e.g. crime types often had typos, as well as having values that overlapped with each other)
```Python
example of cleaning
```

## 3. Visualizations) 

### Streams, Songs, and Artists
- Heatmap of arrests per precinct/borough
- Boros ranked most to least arrests: Brooklyn, Manhattan, Bronx, Queens, Staten Island
<img src="https://github.com/kennyhj/nypd_arrests/blob/main/images/heatmap.jpg" width="500">

### Keys and Modes
- Clustered stacked bar chart of demographics data: race, gender, and age group
- Black males age 25-44 have the highest arrest rates, followed by White-Hispanic males age 25-44
- (There is no sole Hispanic race value in this dataset, it is divided as White-Hispanic and Black-Hispanic) 
<img src="https://github.com/kennyhj/nypd_arrests/blob/main/images/demographics.jpg" width="600">

### Release Year
- Stacked bar chart of the NYC 2020 Census displaying populations by race per borough
- The black population accounts for the 3rd highest population in NYC despite having the highest arrest rates
<img src="https://github.com/kennyhj/nypd_arrests/blob/main/images/census_2020_nyc.jpg" width="600">

### Song Qualities , BPM, and Playlists
- Line graph of # of arrests per year (2006 - 2023)
- A downward trend in the 2010s, but then saw a significant rise starting in 2020
<img src="https://github.com/kennyhj/nypd_arrests/blob/main/images/yearly.jpg" width="550">

## 4. Final Takeaways
- When producing our next viral song we want:
  -  C# major key
  -  high danceability
  -  energy
  -  90-120 BPM
  -  addition to many Spotify playlists
- Further insights that would be useful to pursue:
  - genre
  - TikTok sound usage
  - YouTube data
