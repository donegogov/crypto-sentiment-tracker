# crypto-sentiment-tracker


# CryptoSentiment Tracker

Personal dashboard for tracking discussion trends and sentiment 
across cryptocurrency subreddits.

## What it does

- Monitors public posts from crypto-related subreddits
- Tracks posting frequency, trending topics, and discussion volume
- Stores metadata locally for historical trend analysis
- Generates charts and visualizations for personal research

## Tech Stack

- Python 3.12
- asyncpraw (Reddit API client)
- SQLite (local storage)
- matplotlib (charts)

## Monitored Subreddits

- r/Bitcoin
- r/Cryptocurrency
- r/Solana
- r/Ethereum
- r/Monero
- r/Polkadot
- r/WallstreetBets
- r/Cryptomarkets

## Setup

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Add Reddit API credentials to `.env`
4. Run: `python tracker.py`

## Notes

- Read-only access, no posting or commenting
- All data stored locally
- Runs within Reddit API rate limits (< 60 requests/min)
- For personal investment research only
