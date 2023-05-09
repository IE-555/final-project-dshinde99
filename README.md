[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/6ebMFVGY)
# IE 555 Project Proposal


## Team Members:  
Devang Shinde, devangat@buffalo.edu

Shriram Madkar, shrirams@buffalo.edu 

Gulshankumar Gupta, gulshank@buffalo.edu

Pushkraj Rane, pushkraj@buffalo.edu 



## Proposed Project Title

Data analysis and exploration of Spotify API data


## Project Type
Option 2 - Online Data Analysis

Option 2 - Online Data Analysis

> Students may develop their own programming project. In this option, students must identify a source of online data, which will be dynamically imported via Python. The Python code must utilize these data to either make decision support recommendations or provide a detailed analysis of the data. A YouTube video describing the mechanics of the Python code will be required, in addition to a “how-to” guide for running the code. All source code must be submitted, and the course instructor must be able to execute the code without errors.



## Data Sources

•	Spotify API is used as a data source.

•	The Spotify API (Application Programming Interface) allows developers to access data from the Spotify music streaming service, and build applications that can interact with Spotify's music catalog, user data, and playlists.

•	To use the Spotify API, we need to register our application with Spotify and obtain an access token, which is required to authenticate API requests. The access token must be included in the header of every API request, along with other parameters

•	Here is the link to the Spotify API documentation: https://developer.spotify.com/documentation/web-api 

•	After creating a spotify account or logging into an existing one, the user can create an API documentation and receive unique Developer’s credentials : Client_id and Secret_id, which will be used to fetch and import data.



## Analysis Plan

The objective of this project is to develop a recommendation system for Spotify tracks based on user preferences, such as artist ID, genre, and track ID, using the Spotify API. 

We will also explore the relationships between different music features and track popularity and create visualizations to help understand the data better. 

Once we have imported the Spotify data into our Python environment and installed necessary packages, our first step will be to pre-process the data.

This includes treating/checking for any missing values and removing unnecessary data to ensure accurate analysis.

We will then move on to data exploration and visualization, utilizing Python's data analysis libraries to gain insights into the data.

Through data visualization, we can identify patterns and trends within the Spotify data, such as the relationship between different variables like - artist popularity and genre preference.



## Motivation

The motivation for this project is to create a recommendation system that suggests tracks based on user preferences and gain insights into what makes a track popular, informing music production decisions. From a technical perspective, the project provides an opportunity to explore data analysis, including data visualization, feature engineering, and classification by working on real world data.  This will also provide valuable experience in data wrangling and working with web-based data sources, which are in high demand in many industries.


## Task List
| ID | Task Description | Due Date | Status |
| --- | --- | --- | --- |
| 1 | Update this table with detailed list of tasks | 2023-05-08 | DONE |
| 2 | Acquiring Spotify API Credentials - Acquiring API key and installing Spotify library  | 2023-04-16 | DONE |
| 3 | Importing required data - Retrieving information on the 1000 most popular songs from 2022, including artist name, track name, track popularity, artist id, and track id, etc in a data frame  | 2023-04-22 | DONE |
| 4 | Feature selection - Selecting and retrieving audio features for created data frame ( track_df ) using the API data  | 2023-04-23 | DONE |
| 5 | Data Preprocessing - Performing some data cleaning and manipulation, including dropping unnecessary columns, changing data types and sorting  | 2023-04-30 | DONE |
| 6 | Data Visualization - Performing some exploratory data analysis on the data, including creating bar charts and heatmaps to visualize the data  | 2023-05-06 | IN PROGRESS |
| 7 | Model Development - Create “sp.recommendations” to generate a list of recommended tracks based on set of input parameters | 2023-05-12 | PENDING |
| 8 | Complete YouTube video and upload to YouTube | 2023-05-16 | PENDING |
| 9 | Upload README.md document to Github | 2023-05-17 | PENDING |
