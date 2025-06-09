# 💹 Crypto Dashboard

A dynamic cryptocurrency dashboard built with **Node.js**, **Express**, and **EJS**, which fetches real-time data from the [CoinGecko API](https://www.coingecko.com/en/api). It displays key financial metrics, charts, and sentiment data for popular cryptocurrencies like Bitcoin, Ethereum, Dogecoin, and more.

![screenshot](https://ik.imagekit.io/pyf4swq6nz/localhost_3000_.png?updatedAt=1749456769072)

---

## 🚀 Features

- 📈 Real-time market data for top cryptocurrencies.
- 📊 Interactive charts using **ApexCharts** for:
  - Market Price (INR)
  - Market Cap
  - Market Volume
- 📉 Metrics including:
  - Current Price
  - Market Cap & 24H Change
  - All-Time High/Low
  - Price Change in 24Hrs
  - Volume & Circulating Supply
  - Twitter Followers
- 🌙 Dark-themed responsive UI with Bootstrap Dark.

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express
- **Frontend:** EJS Templates, Bootstrap 5 (Dark Theme), ApexCharts
- **Data Source:** CoinGecko Public API

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/nishhhanth/Crypto-Dashboard.git
cd Crypto-Dashboard

# Install dependencies
npm install

# Start the server
nodemon index.js
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📂 Project Structure

```
Crypto-Dashboard/
├── public/              # Static assets (optional, currently unused)
├── views/
│   └── index.ejs        # Main dashboard page
├── index.js             # Server-side logic and routing
├── package.json
```

---

## 🔧 How It Works

- Users select a cryptocurrency from the dropdown.
- The app fetches data from CoinGecko for:
  - Coin market stats
  - 30-day historical chart data
- The dashboard is updated dynamically with the selected coin's metrics and charts.

---

## 📸 Sample Coins Supported

- Bitcoin (BTC)
- Ethereum (ETH)
- Dogecoin (DOGE)
- Solana (SOL)
- Ripple (XRP)
- Cardano (ADA)
- Binance Coin (BNB)
- Tether (USDT)
- Avalanche (AVAX)
- Decentraland (MANA)
