# Naruto Shippuden Episode Analysis 
This repository analyzes and visualizes data related to the popular anime series, Naruto Shippuden. It explores various aspects of the episodes, including ratings, writers, air dates, and more.

**Dataset**
* Contains information about each episode (title, season, number, director, writer, air dates, rating, votes, description, type)
* Initially had 1500 rows and 12 columns
  
**Data Cleaning**
* Handled missing values: dropped 1000 NaN values in the "type" column
* Removed unnecessary columns: "english_air_date" and duplicate titles were dropped

**Data Visualization and Analysis**
***Descriptive Statistics:***
* Average rating: 7.29
* Total episodes: 500
* Top/Lowest Rated Episodes:
* Scatter plot of votes vs. ratings
* Histograms for episode lengths and air dates
* Bar plot visualizing the average rating per writer

**Dependencies**
* Python 3.x
* Pandas
* Matplotlib
* Seaborn
