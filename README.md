
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
Run the data scraping script to collect the required data:
```bash
python scripts/data_scraping.py
```
Open the Jupyter Notebook for analysis:
```bash
jupyter notebook notebooks/Stock_Sentiment_Analysis.ipynb
```
# Analysis Results

## Key Findings

Sentiment Analysis:
- Stock X shows a significant positive sentiment in discussions,  correlating with a price increase over the last month.
- Stock Y has frequent mentions, but sentiment is predominantly negative, which coincides with a downward price trend.
 
 ## Actionable Insights
- Stock X: The positive sentiment indicates a potential buy signal; traders may consider investing.

- Stock Y: The negative sentiment coupled with price drops suggests caution; traders may consider selling or avoiding this stock.
## Recommendations

- Integrate additional data sources, such as financial news and reports, to enhance the analysis.
- Utilize advanced sentiment analysis techniques like deep learning for more nuanced insights.
