# dsa210-project

# Analysis of My YouTube Data
## Introduction
The main interest in this project is getting a better understanding of my Youtube viewing habits and exploring patterns that may exist in my history. I want to determine the kind of videos I watch the most and calculate the average time spent watching Youtube every day. This will enable me to learn whether I spend more time on YouTube than I declare, and how I can optimize my choices when it comes to video selection and discovery based on my historical preferences.

## Data Collection
Data used for this project was retrieved via Google Takeout.
Data downloaded includes:
* Watch History: Videos watched with the title of the videos and the time watched.
* Subscriptions: A list of all the YouTube channels I am subscribed to, along with subscription dates.
* Likes/Dislikes: Information about the videos I liked/disliked.
 
The data downloaded is analyzed and pre-processed using Python.

## Data Preprocessing
I conducted the following preprocessing steps to structure the data:
 
* Cleaning Data: I cleaned my YouTube data by removing irrelevant entries and incomplete entries.
* Datetime Parsing: Timestamps were converted to Python datetime objects for easier analysis based on time.
* Feature Extraction: Extracted the relevant features such as video categories, video lengths, video titles, like counts, and dislike counts of each video.
* Data Structuring: Converted data into a structured format of pandas dataframe for better analysis of data.

## Analysis
I have conducted the subsequent analyses on the YouTube Data:

* Watch History Analysis:  
I looked into the number of videos viewed daily, weekly, and monthly. The overall watch time was calculated and visualized through time series plots for the observation of any sharp changes in the viewing patterns.
* Most Watched Genres:  
I categorized the videos according to their genre. The distribution of frequency of the videos belonging to each category was shown through bar charts, where I also calculated the average amount of videos watched by category.
* Interaction Patterns:  
I analyzed the rate at which I liked or disliked videos and the types of videos that I interacted with most.
* Subscription Trends:  
I investigated my interactions with subscribed channels.
* Engagement Analysis:  
I analyzed how video length correlates with my watch time and engagement, comparing videos I watched fully versus those I skipped.

