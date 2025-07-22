# Investment Dashboard (Stocks + Crypto)

📈 A PyQt6-based desktop application that fetches trending stock and cryptocurrency news, extracts tickers using NLP, displays sentiment and price info, and sends Discord alerts for hot picks.

---

## Features

- Fetches latest headlines from multiple financial news RSS feeds
- Extracts stock and crypto tickers using spaCy and regex
- Retrieves real-time price and percentage change from Finnhub API
- Displays ticker data sorted by mentions, sentiment, or price
- Dark mode UI with filtering and sorting options
- Sends throttled Discord alerts for highly positive or negative sentiment picks
- AI picks tab shows top 3 stocks/cryptos based on sentiment and mentions
