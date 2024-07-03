# Comment Scrapper of HPCL YouTube Playlists and Sentiment Analysis

## Introduction
This project involves scraping comments from HPCL (Hindustan Petroleum Corporation Limited) YouTube playlists and performing sentiment analysis on the collected comments. The goal is to understand public sentiment towards HPCL's videos and gather insights on viewer opinions.

## Objectives
- Scrape comments from YouTube playlists of HPCL.
- Analyze the sentiment of the collected comments.
- Generate a report summarizing the findings.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Google API Client Library for Python
- pandas
- nltk (Natural Language Toolkit)
- TextBlob

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/aishwarayajimin/Comment-Scrapper-of-Hpcl-YouTube_Playlists-and-Sentiment-Analysis
    cd repository_name
    ```

2. **Install required packages:**
    ```bash
    pip install google-api-python-client pandas nltk textblob
    ```

3. **Obtain YouTube Data API key:**
    - Go to the [Google Developers Console](https://console.developers.google.com/).
    - Create a new project and enable the YouTube Data API v3.
    - Create API credentials and note the API key.

## Notebook Overview
### 1. Setup and Imports
- Import necessary libraries.
- Set up YouTube Data API client.

### 2. Scraping YouTube Comments
- Define a function to get comments from YouTube playlists.
- Extract comments using the YouTube Data API.
- Store the comments in a pandas DataFrame.

### 3. Preprocessing Comments
- Clean and preprocess the comments for sentiment analysis.
- Tokenize comments and remove stop words.

### 4. Sentiment Analysis
- Perform sentiment analysis using TextBlob and nltk.
- Calculate the sentiment polarity and subjectivity of each comment.
- Classify comments as positive, negative, or neutral based on polarity.

### 5. Results and Visualization
- Summarize the sentiment analysis results.
- Visualize the distribution of sentiments using plots.
- Generate a report of the findings.

## Conclusion
This project successfully scrapes comments from HPCL YouTube playlists and performs sentiment analysis to understand public opinion. The results provide valuable insights into viewer sentiment, which can help HPCL in improving their content and engagement strategies.

## Future Work
- Extend the scraper to include more YouTube playlists.
- Enhance the sentiment analysis with more advanced techniques.
- Integrate with a web dashboard for real-time sentiment monitoring.

## Acknowledgments
- [YouTube Data API](https://developers.google.com/youtube/v3)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)
- [nltk](https://www.nltk.org/)


