# Twitter-Analysis-of-30DAYSOFLEARNING
![Screenshot 2023-04-14 022139](https://user-images.githubusercontent.com/115046602/232083736-03d28751-95cf-4252-ad0d-327c930ef6ac.png)![Screenshot 2023-04-15 051759](https://user-images.githubusercontent.com/115046602/232182590-35968ccd-5066-4a17-8187-1ee46ee9c511.png)


# Introduction
An analytical breakdown of tweets on the #30DAYSOFLEARNING on Data Analysis in the month of June 2022, showing total number of tweets for that month, total number of users, tools by mentions etc using PowerBi

# Project Overview
This program was made to help people upskill with Microsoft technologies by learning and building solutions across these knowledge areas; Data Analysis Using Power Bi, , Low-code/No-Code Application Development using Power Platform, and Data Science and Machine Learning with Azure.

# Data Sourcing
The scrapped data was gotten from GitHub: https://aka.ms/30DLDATGitHubRepo and downloaded as a csv file.

# Data Cleaning
Data was transformed and cleaned in Power Query. Data cleaning is a process that modifies and remove unneccesary, irrelevant, inproperly formatted, incorrect and duplicated data.

# Data Cleaning Process
After importing the Data to PowerBi as csv, columns were duly renamed for better analysis. Initially, the dataset included the data for both the month of May and June, so it was filtered to display only the data for June. Date column was duplicated and Day name was extracted (Saturday, Sunday, Monday etc) and the first three characters were extracted from the Date Name in a new column (Sat, Sun, Mon etc). The date column contained both date and time so it was spilt by delimiter into a new column.

# Power Query
The data was finally loaded to PowerBi desktop for analysis and visualization

# Analysis
The following insights were drawn from the data
1. Total no. of tweets
2. Total number of Users
3. Highest number of tweet in the week
4. Highest number of tweets by source (Android, Iphone, Web)
5. Top five tweets by user
6. No. of tweets by month and day
7. Top twitter Handles
8. Tools by mentions
9. User Tweets


# Conclusions
1. Data was collected for 25 days in the month of June but 23 days were visualized. This was investigated and was found out that there was no data for the 3rd and 4th most likely because the numbers rounded up to zero so there were no data on them. In 23 days, there were 645 tweets from 197 users. The top twwets by a user and top twitter handler form the #30DAYSOFLEARNING is 'TheOyinbooke' 
2. People were tweeting from Android than from web or iphone
3. Wednesdays got the highest tweets in the month
4. The most mentioned tool is Github with 109 metions followed by Excel 29, Azure 26 and PowerBi 19 mentions
