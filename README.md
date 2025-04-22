# YouTube Data Analysis with Python
Analyze and visualize YouTube channel and video data using the YouTube Data API, Pandas, and Seaborn.

## Project Overview
This project demonstrates how to:

Access the YouTube Data API

Fetch channel and video statistics

Structure data using Pandas

Create insightful visualizations using Seaborn

## Features
🔑 Generate and manage YouTube API keys

📥 Extract channel metadata: name, subscribers, views, video count

📼 Extract video-level metrics: views, likes, comments, publish dates

## Visualize:

Top videos by views

Upload frequency by month

Channel comparison plots

## Tech Stack
Python 

Google API Client

## Setup Instructions
Clone the Repository
```
git clone https://github.com/yourusername/youtube-data-analysis.git
cd youtube-data-analysis
```
Create and Activate Virtual Environment
```
conda create --name yt_env python=3.9
conda activate yt_env
```
Install Dependencies
```
conda install google-api-python-client pandas seaborn jupyter
```
Run the Notebook
```
jupyter notebook
```

## 🔑 How to Get YouTube API Key
Go to [Google Developer Console](https://console.cloud.google.com/apis/dashboard?pli=1&project=yt-analysis-project-1808)

Create a new project

Enable YouTube Data API v3

Create an API key under Credentials

## Output
Cleaned Pandas DataFrames

Bar plots showing:

Channel subscriber comparison

Views vs. video count

Monthly video upload trends

CSV file output of all video data
