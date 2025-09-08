YouTube Data Analysis – News Publishers
# Overview

This project analyzes YouTube video data from news publishers.
It connects to the YouTube Data API, collects video metadata (views, likes, comments, publish times, etc.), and performs analysis/visualization in Python.

The goal is to understand content patterns and audience engagement across different news publishers.

# Project Contents

Project Code.ipynb → Main Jupyter Notebook with code and analysis.

collect.ipynb → Data collection pipeline from YouTube API.

HD1.ipynb → Task notebook for advanced analysis.

credentials-sample.ini → Sample config file for storing YouTube API key (rename to credentials.ini and add your own key).

directions.pdf → Instructions and guidelines.

# Setup & Installation

Clone the repository

git clone https://github.com/<your-username>/Python-Project.git
cd Python-Project


Create a virtual environment (recommended)

python -m venv venv
source venv/bin/activate    # On Mac/Linux
venv\Scripts\activate       # On Windows


Install dependencies

pip install -r requirements.txt


(Create requirements.txt with libraries like pandas, numpy, matplotlib, google-api-python-client, etc.)

# API Credentials

Go to Google Cloud Console
.

Create a project & enable YouTube Data API v3.

Generate an API key.

Copy credentials-sample.ini → rename to credentials.ini.

Paste your key inside:

[credentials_youtube]
developer_key = YOUR_API_KEY
youtube_api_service_name = youtube
youtube_api_version = v3

# How to Run

Open Jupyter Lab or Notebook:

jupyter lab


Run cells in collect.ipynb to gather YouTube data.

Run Project Code.ipynb or HD1.ipynb for analysis & visualization.

# Features

Fetch video data from YouTube API.

Analyze publisher performance.

Visualize engagement (views, likes, comments).

Explore content upload frequency and audience interaction.

# Notes

Make sure you keep your API key private.

Use credentials.ini (not credentials-sample.ini) for real runs.

# Academic Context

Unit: SIT112 – Data Science Concepts

Task: HD1 – Analyzing YouTube Video Data from News Publishers