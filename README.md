# luxcapstoneproject
# Kenya YouTube Channels Analysis

This project analyzes various Kenyan YouTube channels using the YouTube API. The analysis includes extracting data from the YouTube API, performing exploratory data analysis (EDA), and visualizing the results using Python libraries such as Matplotlib and Seaborn.

## Project Overview
This project focuses on analyzing Kenyan YouTube channels to understand trends in subscribers, views, and videos. By using the YouTube API, data was collected and processed for various YouTube channels, and different analyses were performed to gain insights into the growth and popularity of these channels over time.

## Dataset
The dataset consists of metadata collected from Kenyan YouTube channels using the YouTube API. The main features include:
- **Channel Title**
- **Description**
- **Subscribers**
- **Views**
- **Videos**
- **Published Date**

## Features
- **Data Extraction**: Extract data using the YouTube API.
- **Exploratory Data Analysis (EDA)**: Visualize distributions, time series analysis, and correlation analysis of channel metrics.
- **Time Series Analysis**: Explore trends in subscribers, views, and videos over time.
- **Correlation Analysis**: Analyze the relationship between subscribers, views, and videos.

## Installation
To run this project, you'll need to have Python installed on your system. You can install the required dependencies using `pip`.

1. Clone the repository:
   ```bash
   git clone https://github.com/ashitech/luxcapstoneproject.git
   cd kenya-youtube-analysis
   pip install -r requirements.txt
   setx YOUTUBE_API_KEY "your_api_key_here"
   python analysis_script.py


