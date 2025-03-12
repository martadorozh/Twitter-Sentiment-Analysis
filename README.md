# TweeterAnalysis
BTC analysis using Twitter &amp; NLP

Social media such as Facebook, Instagram, or Twitter are places where many people spend some of their free time, writing various messages, uploading photos and videos. The profiles of individual users and the content they publish are the source of a huge amount of information that can be used as data for various analyzes and research. Cryptocurrencies are similar to the most famous currencies in the sense that they are constructed under the influence of public opinion, whether they are factual or not.

In this project, I wanted to analyze the impact of Twitter users' statements on cryptocurrency price predictions through natural language processing using sentiment analysis.

This project performs web scraping on Twitter data to analyze tweets using the Twitter API. The project utilizes Python libraries for data collection, processing, analysis, and visualization. The goal is to explore topics, trends, and sentiment analysis of tweets.

## Table of Contents

1. [Project Description](#project-description)
2. [Installation and Setup](#installation-and-setup)
3. [Usage](#usage)
4. [Sample Results](#sample-results)
5. [License](#license)
6. [Contact](#contact)

## Project Description

This project uses **Tweepy** to collect tweets via the Twitter API. The collected data is then processed and analyzed using **pandas**, **matplotlib**, and **seaborn** for data visualization. The project allows for:

- Collecting tweets using specific keywords or hashtags.
- Data preprocessing, including cleaning and filtering.
- Sentiment analysis of tweets (positive, negative, neutral).
- Visualization through charts and graphs.

## Installation and Setup

### 1. Clone the repository:

```bash
git clone https://github.com/martadorozh/TweeterAnalysis-Web-Scraping.git
cd TweeterAnalysis-Web-Scraping
```

### 2. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

### 3. Install required dependencies:

```bash
pip install -r requirements.txt
```

### 4. Set up Twitter API:

To access the Twitter API, you need to create a Twitter Developer account at [developer.twitter.com](https://developer.twitter.com/) and obtain your API keys. Add these keys to a `.env` file:

```
TWITTER_API_KEY=<your_api_key>
TWITTER_API_SECRET=<your_api_secret>
TWITTER_ACCESS_TOKEN=<your_access_token>
TWITTER_ACCESS_TOKEN_SECRET=<your_access_token_secret>
```

### 5. Run the project:

Run the Jupyter notebook `TweetsAnalysis.ipynb`:

```bash
jupyter notebook TweetsAnalysis.ipynb
```

## Usage

In this project, you can:

- Collect tweets using specific keywords or hashtags.
- Clean and preprocess the text data for analysis.
- Perform sentiment analysis (positive, negative, neutral).
- Generate visualizations, such as sentiment distribution and popular hashtags.

The process for data collection and analysis is documented in the `TweetsAnalysis.ipynb` notebook.

## Sample Results

After running the analysis, you will get results like:

- Sentiment distribution charts of the tweets.
- Visualizations of the most popular hashtags.
- Trending topics based on the collected tweets.

## License

This project is licensed under the [MIT License](LICENSE).

This README provides an overview of your project in English, including instructions for setup, usage, and sample outcomes. If you want to change the project name or need further modifications, feel free to let me know!
