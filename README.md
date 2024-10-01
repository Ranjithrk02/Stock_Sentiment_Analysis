
# Stock Movement Analysis Based on Social Media Sentiment

# Project Overview
This project aims to analyze and predict stock movements by extracting and analyzing social media data from platforms like Reddit. By performing sentiment analysis on social media discussions related to specific stocks, this project provides insights into potential price trends and signals for buy/sell decisions.
# Objective
The objective of this project is to understand the relationship between social media sentiment and stock price movements. By scraping relevant data, performing sentiment analysis, and correlating these insights with stock prices, we aim to uncover actionable insights for traders and investors.
# Setup Instructions



## Prerequisites
Ensure you have Python installed (version 3.6 or higher) and have `pip` available for package management.





## Installation

Clone the repository to your local machine:

```bash
git clone <repository-url>
cd Stock_Sentiment_Analysis
```
Install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
```
 ### Get API Keys

 You will need API keys to access Reddit API:

 ### Reddit API:
- Go to the Reddit App Preferences.
- Click on "Create App" or "Create Another App."
- Fill in the required fields. Select the script option.
- Note the `client_id`, `client_secret`, and `user_agent`.

### Configure API Keys:

REDDIT_CLIENT_ID = `your_reddit_client_id`

REDDIT_CLIENT_SECRET = `your_reddit_client_secret`

REDDIT_USER_AGENT = `your_reddit_user_agent`

Run the data scraping script to collect the required data:
```bash
python scripts/data_scraping.py
```
Open the Jupyter Notebook for analysis:
```bash
jupyter notebook notebooks/Stock_Sentiment_Analysis.ipynb1
```
- Open the notebook and run the cells to perform sentiment analysis and feature extraction.

#### Visualize Results

The notebook contains code for visualizing the results. Run the corresponding cells to generate the visualizations.

### Data Collection
- Input: Raw data from Reddit (e.g., posts from r/wallstreetbets).
- Output: Cleaned dataset containing sentiment scores, post metadata, and stock mentions.

### Analysis and Feature Extraction
- Input: Cleaned data from the scraping step.
- Output:
- Sentiment scores (positive, negative, neutral)
Frequency of mentions
- Additional features for correlation analysis

# Analysis Results

## Visualization
- Input: Results from the analysis step.
- Output: Visualizations (charts, graphs) that show trends in stock sentiment, Frequency of Mentions Over Time and Correlations between sentiment and stock price movements.


## Screenshots

![App Screenshot](Screenshots/Screenshot%202024-10-02%20005211.png)

![App Screenshot](Screenshots/Screenshot%202024-10-02%20005256.png)

## Sentiment Counts
- Neutral Sentiments: 298 occurrences
- Negative Sentiments: 2 occurrences
This indicates that a vast majority (approximately 99.3%) of the comments are neutral, with only a minimal presence of negative sentiment.

## Stock Mentions
- Total Mentions of AAPL: 0 mentions

This suggests that there were no discussions regarding the stock AAPL in the comments analyzed. This could indicate a lack of interest in AAPL in the context of the discussions on the specific subreddit or threads examined.

## Recommendations Based on Findings
- Broaden Data Collection: To obtain a more comprehensive view, consider scraping additional subreddits or posts related to stocks or more popular stocks to capture relevant discussions and sentiments.

- Analyze Other Stocks: If AAPL is not being mentioned, it may be beneficial to track discussions around other stocks that are currently trending or of interest to the audience, such as those in the news or actively traded.

- Sentiment Analysis Model Evaluation: Given the overwhelming neutrality in sentiment, reviewing the sentiment analysis model's configuration may help enhance its sensitivity and accuracy in capturing a broader range of sentiments, especially positive ones.

- Monitor Changes Over Time: It might be valuable to conduct this analysis over different time periods to observe trends and changes in sentiment and stock mentions. This could help identify any potential correlations with stock price movements.




