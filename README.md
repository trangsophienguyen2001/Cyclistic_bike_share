# Case Study Cyclistic Bike Share

## Scenario 

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes 
the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and 
annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual 
members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data 
visualizations.

## Ask/Business Task

#### Questions: How do annual members and casual riders use Cyclistic bikes differently?

### Business Task: To identify and understand the bike usage among annual members and casual riders in order to suggest marketing strategies to convert casual riders into annual members. 

## Prepare

I will use Cyclistic’s historical trip data located here to analyze and identify trends. The [data](http://divvy-tripdata.s3.amazonaws.com/index.html) has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement). This is a public dataset that I can use to explore how different customer types are using Cyclistic bikes. Note there is no personal data and this means that I won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes. 

Some key columns are worth noting are:
•	Start_station_name
•	End_station_name
•	Start_station_id
•	End_station_id
•	Started_at
•	Ended_at
•	Member_casual
•	Station latitude and longitude columns (for data visualization)

## Process
This step will prepare the data for analysis. I will be using RStudio for this project. 
Key tasks:
Download data and store it appropriately.
Identify how it’s organized.
Sort and filter the data.
Determine the credibility of the data.
[Clean data](https://github.com/trangsophienguyen2001/Cyclistic_bike_share/blob/main/Cyclistic_clean_data.Rmd)

## Analyze
This step will explore the distribution of casual riders & annual members and how these two groups differ from each other.
Key tasks: 
Aggregate your data so it’s useful and accessible.
Organize and format your data.
Perform calculations.
Identify trends and relationships.
[Analyze data](https://github.com/trangsophienguyen2001/Cyclistic_bike_share/blob/main/Cyclistic_analyze_data.Rmd)

## Share
With the insights gained from the previous steps, I have created a presentation with all the main points, let's go through them together [here](https://github.com/trangsophienguyen2001/Cyclistic_bike_share/blob/main/Cyclistic%20Presentation.pdf).

## Act 
Partner with influencers to create a marketing campaign focusing on healthy lifestyles and promoting an eco-friendly approach to protecting the environment by reducing car emissions. The ads can be shown on social networks such as TikTok, Instagram posts, or reels.
Offer discounts and special programs during the cold months.
Create an ad promoting how practical and beneficial riding the bikes can be, focusing on casual riders during the weekends.
