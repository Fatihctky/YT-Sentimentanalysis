# YT-SentimentRadar

YT-SentimentRadar is a Python-based sentiment analysis and visualization tool for YouTube comments. 
It fetches comments from any public video using the YouTube Data API v3, performs emotion classification (positive / negative / neutral), and visualizes the results with bar charts and word clouds. It also includes an interactive Streamlit web interface.
 📌 This project has been tested on real-world financial videos including topics such as stock market analysis, investment advice, and economic discussions.


## 🚀 Features

- Fetches top-level comments from any YouTube video  
- Performs sentiment analysis using TextBlob  
- Generates word clouds from comment text  
- Visualizes sentiment distribution  
- Streamlit-based user interface  
- Exports all comments to CSV


## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Fatihctky/YT-Sentimentanalysis.git
cd YT-Sentimentanalysis

# 🔑 How to Get a YouTube Data API Key

To use this project, you need a valid YouTube Data API key.
Follow the steps below to generate your own key and start analyzing comments from any public YouTube video.


## 📌 Step-by-Step Instructions

### 1. Go to Google Cloud Console
Open: https://console.cloud.google.com/

> Make sure you're logged in with your Google account.


### 2. Create a New Project
- Click **“Select a project”** (top bar)
- Then click **“New Project”**
- Enter a name (e.g., `YT-SentimentRadar`) and click **Create**


### 3. Enable the YouTube Data API
- From the left menu:  
  **APIs & Services > Library**
- In the search bar, type:  
  `YouTube Data API v3`
- Click on it, then click **Enable**


### 4. Create an API Key
- Go to:  
  **APIs & Services > Credentials**
- Click **“+ Create Credentials” > API Key**
- A dialog will pop up with your new key  
  → Copy that key


### 5. Use Your API Key in the Project

- In the root folder of the project, create a `.env` file  
- Paste your key inside it like this:
