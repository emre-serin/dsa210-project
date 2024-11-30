# dsa210-project

# Analysis of My Youtube Watch History
## Introduction
My motivation for this project is to better understand my YouTube viewing habits and explore patterns in my Youtube history. I hope to identify the types of videos I watch the most and how my engagement with certain content changes over time. This analysis can help me understand whether I spend more time on YouTube than I intend, how to optimize my viewing choices, and find new content based on my historical preferences.

## Data Collection
The data for this project was collected through Google Takeout from which I downloaded the data of my Youtube account. 
The data I downloaded includes:

* Watch History: Information about the videos I've watched, including video titles, timestamps, and video duration.  
* Subscriptions: A list of all the YouTube channels I am subscribed to, along with subscription dates.  
* Likes/Dislikes: Data on the videos I have liked or disliked.  
  
The downloaded data is stored in JSON format, which will be parsed and analyzed using Python.

## Data Preprocessing
I conducted the following preprocessing steps to organize data:  
* Data Cleaning: I removed irrelevant or incomplete entries from my YouTube data.
* Datetime Parsing: Timestamps were converted into Python datetime objects to make time-based analysis easier.
* Feature Extraction: Extracted relevant features like video categories, video length, video titles, and like/dislike counts.
* Data Structuring: The JSON data was converted into structured pandas dataframe for easier analysis.

## Analysis
The following analyses were performed on my YouTube data:

* Watch History Analysis:  
I analyzed the number of videos watched per day, week, and month. The total watch time was calculated, and trends were visualized using time series plots to observe any significant changes in viewing habits.
* Most Watched Genres:  
I categorized videos by genre. The frequency of videos from each category was visualized using bar charts, and I calculated the average number of videos watched per category.
* Interaction Patterns:  
I analyzed how often I liked or disliked videos, and the types of videos I interact with the most.
* Subscription Trends:  
I explored the frequency of my interactions with subscribed channels.
* Engagement Analysis:  
I analyzed how video length correlates with my watch time and engagement, comparing videos I watched fully versus those I skipped.

