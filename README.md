📊 YouTube Data Scraping & Analysis (Jupyter Notebook)
📌 Project Overview

This project demonstrates how to scrape and analyze YouTube data using the YouTube Data API and Python.
The goal is to extract channel and video details, analyze them using Pandas, and create visualizations using Seaborn.

The project is divided into two main parts:

Extracting channel details (subscribers, views, total videos) and comparing multiple channels.

Extracting video details from a channel (title, views, likes, comments) and analyzing them with visualizations.

🛠 Tools & Technologies

Python

Jupyter Notebook

Pandas

Seaborn

Google API Python Client (google-api-python-client)

Anaconda (for virtual environment management)

Git & GitHub

        YouTube-Scraping-Analysis/
        │── notebooks/
        │   └── ScrapingYT.ipynb
        │── data/                # optional, for storing CSV or intermediate data
        │── README.md
        │── requirements.txt



▶️ Step-by-Step Guide
1️⃣ Create a YouTube API Key

Go to the Google Cloud Console

Create a new project and enable the YouTube Data API v3.

Generate an API Key—this will be used to access YouTube data in Python.

2️⃣ Explore YouTube API Documentation

Understand resources and methods to fetch different types of data (channels, videos, playlists).

Look at sample Python code provided by Google to get familiar with API calls.

3️⃣ Set Up the Python Environment

Create a new virtual environment using Anaconda:

conda create -n youtube_env python=3.10
conda activate youtube_env

Install required packages:

pip install google-api-python-client pandas seaborn

4️⃣ Write the Code in Jupyter Notebook

Open ScrapingYT.ipynb in Jupyter Notebook.

Part 1: Channel Data Extraction

Extract channel details:

Name

Total subscribers

Total views

Number of videos

Gather data for multiple channels, load into a Pandas DataFrame, and generate basic visualizations to compare channels.

Part 2: Video Data Extraction

Extract video details for a selected channel:

Title

Total views

Likes, Favorite, comments

Load data into a Pandas DataFrame and create visualizations using Seaborn for analysis.


        
