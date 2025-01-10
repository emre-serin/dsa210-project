# dsa210-project

# Analysis of My YouTube Data
## Introduction
The main interest in this project is getting a better understanding of my changing YouTube habits. I believe that I tend to watch shorter videos or watch videos for a shorter time interval for the last 1 year. That's why I wanted to analyze if there is such a significant decrease in duration that I choose to watch YouTube videos between 2023 and 2024. This project analyzes and compares my YouTube data regarding 2023 and 2024 to test the null hypothesis that the average duration of videos watched for less than 60 seconds in 2024 is the same as the average duration of such videos in 2023.

## Data Collection
Data used for this project was retrieved via Google Takeout.
Data downloaded includes:
* Watch History: Videos watched with the title and link of the videos and the time that I started to watch the video.

The data downloaded is analyzed and pre-processed using Python (Google Colab).

## Data Preprocessing
I conducted the following preprocessing steps to structure the data:
 
* Cleaning Data: I cleaned my YouTube data by removing irrelevant entries and incomplete entries.
* Datetime Parsing: Timestamps were converted to Python datetime objects for easier analysis based on time.
* Feature Extraction: Extracted the relevant features such as video lengths and video titles of each video.
* Data Structuring: Converted data into a structured format of pandas dataframe for better analysis of data.

## Analysis
I have conducted the subsequent analyses on the YouTube Data:

* Watch History Analysis:  
Firstly, . The overall watch time was calculated and visualized through time series plots for the observation of any sharp changes in the viewing patterns.

* Engagement Analysis:  
I analyzed how video length correlates with my watch time and engagement, comparing videos I watched fully versus those I skipped.

