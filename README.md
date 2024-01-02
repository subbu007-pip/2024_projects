# Social Media Analytics Toolkit

## Overview

This Python toolkit provides functionalities to collect and analyze data from Twitter and Instagram. It covers sentiment analysis, content analysis, user engagement patterns, influencer identification, and hashtag/trend analysis.

## Prerequisites

- Python 3.x
  ## Case 1
  # Use Developer account for better use (default) ideal for data extractions
- Twitter Developer Account for Twitter API access 
- Instagram Developer Account (for scraping, subject to Instagram's terms)
  ## Case 2
  # Use Thridparty Tools
  - Twint : https://github.com/twintproject/twint
  ## Case 3
  # Using python  module
  -  ntscraper link : https://github.com/zedeus/nitter#installation
      - for the btter understanding and better use case please refere above link and then use
  -  snscrape  link : https://pypi.org/project/snscrape/
## Setup

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
# config.py
TWITTER_API_KEYS = {
    'consumer_key': 'your_consumer_key',
    'consumer_secret': 'your_consumer_secret',
    'access_token': 'your_access_token',
    'access_token_secret': 'your_access_token_secret',
}

INSTAGRAM_USERNAME = 'your_instagram_username'
INSTAGRAM_PASSWORD = 'your_instagram_password'
