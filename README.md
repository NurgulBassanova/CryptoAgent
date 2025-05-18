# 📈 AI Crypto Assistant (Live Off-Chain Data) — Dify AI

This is a no-code AI assistant built with [Dify.AI](https://dify.ai), designed to answer real-time questions about the cryptocurrency market using off-chain data sources. It supports natural language queries about the **Top 50 cryptocurrencies by market cap**.

---

## 🎯 Project Objective

- Build an AI assistant that answers user questions about the **crypto market**
- The assistant pulls live data from:
  - 📰 One **crypto news service**
  - 💰 One **crypto exchange API** (for real-time prices)
  - 📊 One **market data API** (like CoinGecko or CoinMarketCap)

---

## 💡 Example Queries

- “What’s the latest news about **Ethereum**?”
- “What’s the current price and market cap of **Solana**?”
- “Which are the top 5 trending coins this week?”
- “Has Bitcoin gone up in the last 24 hours?”
- “What is the trading volume of XRP?”

---

## 🔗 Live Demo (Dify Share Link)

👉 [Try the AI Crypto Assistant](https://cloud.dify.ai/share/YOUR-BOT-ID)  
_(Replace with your Dify share link)_

---

## ⚙️ Data Sources Used

| Type             | Source                   | API / Notes                           |
|------------------|--------------------------|----------------------------------------|
| News             | CryptoPanic / NewsAPI    | Pulls latest crypto-related news       |
| Price Data       | Binance API / Coinbase   | Gets live prices for top 50 tokens     |
| Market Info      | CoinGecko API            | Market cap, volume, rankings           |

---

## 💬 Features

- ✅ Live querying of crypto news
- ✅ Fetch current prices and market cap
- ✅ Natural language interface via Dify
- ✅ Simple chat interface — no login needed
- ✅ Can be updated to support file uploads or history tracking

---

## 🖼 Screenshots

| News Response | Price Query |
|---------------|-------------|
| ![](screenshots/news.png) | ![](screenshots/price.png) |

---

## 📁 Folder Structure


---

## 🚀 How It Works (Inside Dify)

- **Prompt Template**: Includes API tools to call endpoints for real-time data.
- **Knowledge Base**: Optional for static coin definitions or whitepapers.
- **API Tools**: External API calls to Binance/CoinGecko/CryptoPanic.
- **No-code Workflow**: Entire logic handled via prompt design + tools.

---

## 📚 Future Improvements

- Multi-language support (e.g., Russian, Kazakh)
- Personalized portfolios
- Alert system (price change notifications)

---

## ✍️ Author

- Bassanova Nurgul Myrzabekovna  
- Built using Dify (No-code AI development)


