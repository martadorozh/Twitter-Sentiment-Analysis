# TwitterAnalysis
BTC analysis using Twitter &amp; NLP

Social media platforms such as Twitter have become a powerful source of real-time information and opinions. Users frequently express their thoughts on various topics, including cryptocurrencies, which are highly influenced by public sentiment, whether fact-based or not. Given the volatility of cryptocurrencies, analyzing public sentiment can provide valuable insights into price trends.

In this project, I aim to analyze the impact of Twitter users' opinions on Bitcoin price predictions through Natural Language Processing (NLP) and Sentiment Analysis. By leveraging Twitter data and machine learning techniques, I explore the relationship between market sentiment and cryptocurrency fluctuations.

## Table of Contents

1. [Project Description](#project-description)
2. [Installation and Setup](#installation-and-setup)
3. [Usage](#usage)
4. [Sample Results](#sample-results)
5. [License](#license)

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
