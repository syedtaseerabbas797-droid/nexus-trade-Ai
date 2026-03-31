# 🤖 NEXUS.TRADE — AI Crypto Trading Agent

> Built for **lablab.ai Hackathon** | AI Trading Agents Track

![HTML](https://img.shields.io/badge/HTML-Single%20File-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![Claude AI](https://img.shields.io/badge/Claude-Sonnet%204.6-purple)
![CoinGecko](https://img.shields.io/badge/API-CoinGecko%20Free-green)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🌟 Overview

NEXUS.TRADE is a production-grade AI-powered cryptocurrency trading dashboard that combines **live market data** with **Claude AI intelligence** to generate real-time BUY, SELL, or HOLD trading decisions.

No installation. No build tools. Just open `index.html` in your browser and start trading smarter.

---

## ✨ Features

### 💰 Live Market Data
- Real-time prices for BTC, ETH, SOL, BNB, ADA, XRP
- Auto-refresh every 30 seconds via CoinGecko Free API
- Price flash animations on update (green/red)

### 📈 Interactive Charts
- Line, Area, and Candlestick chart modes
- Hover tooltips with price, date, and % change
- Crosshair on hover
- 52-Week HIGH and LOW indicators
- Volume bars display
- AI decision markers on chart (↑ BUY / ↓ SELL / — HOLD)

### 🤖 AI Trading Agent
- Powered by **Claude Sonnet 4.6**
- Analyzes: price, momentum, volatility, trend, Fear & Greed
- Returns: Decision, Confidence %, Reasoning, Risk Level, Target Price, Stop Loss
- Full analysis in terminal-style output

### 📊 Technical Indicators
- SMA 7 (7-day Simple Moving Average)
- Price Momentum %
- Volatility Level (Low / Medium / High)
- Trend Direction (BULLISH ↑ / BEARISH ↓)

### 😨 Fear & Greed Index
- Live semicircle gauge meter
- Powered by alternative.me Free API
- Extreme Fear → Extreme Greed scale

### 💼 Paper Trading Simulator
- $10,000 virtual starting balance
- Execute BUY/SELL based on AI decisions
- Track holdings, avg price, P&L
- Persistent via localStorage

### 🕒 AI History Log
- Last 5 AI agent runs stored
- Timestamp, coin, decision, summary
- Persistent via localStorage

### 📤 Export Tools
- Copy analysis to clipboard
- Screenshot dashboard as PNG
- Export price history as CSV

### ⚙️ Settings Panel
- Claude API key (stored locally)
- Refresh interval control
- Sound effects toggle
- Animation speed control

---

## 🚀 Getting Started

### Step 1 — Clone or Download
```bash
git clone https://github.com/YOUR_USERNAME/nexus-trade-ai.git
```

### Step 2 — Open in Browser
```
Just double-click index.html
No npm install. No setup. No server needed.
```

### Step 3 — Get Free Anthropic API Key
```
1. Go to console.anthropic.com
2. Sign up (free)
3. Settings → API Keys → Create Key
4. New accounts get $5 free credits
```

### Step 4 — Enter API Key
```
1. Click ⚙ gear icon in dashboard
2. Paste your Anthropic API key
3. Click Save Settings
4. Press "▶ RUN AI AGENT" button
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML / CSS / JavaScript | Frontend (single file) |
| Chart.js | Interactive price charts |
| Claude Sonnet 4.6 | AI trading decisions |
| CoinGecko Free API | Live crypto prices |
| alternative.me API | Fear & Greed Index |
| Web Audio API | Sound effects |
| html2canvas | Screenshot feature |
| localStorage | Data persistence |

---

## 📡 APIs Used

| API | Endpoint | Cost |
|-----|----------|------|
| CoinGecko | `/simple/price` | Free |
| CoinGecko | `/coins/{id}/market_chart` | Free |
| CoinGecko | `/coins/{id}/ohlc` | Free |
| alternative.me | `/fng` | Free |
| Anthropic Claude | `/v1/messages` | Free tier |

---

## 🎨 Design

- **Theme:** Dark Bloomberg Terminal + Cyberpunk
- **Primary Font:** Space Mono (data/numbers)
- **UI Font:** Syne (headings/labels)
- **Accent Color:** `#00e5ff` Cyan
- **Background:** `#0a0e17` Deep Navy

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` | Select Bitcoin |
| `2` | Select Ethereum |
| `3` | Select Solana |
| `R` | Run AI Agent |
| `D` | Cycle Timeframe |

---

## ⚠️ Important Note

> Claude API calls from browser require the header:
> `anthropic-dangerous-direct-browser-access: true`
> For production deployment, use a backend proxy server
> to securely handle API calls.

---

## 👥 Team

Built with for **lablab.ai Hackathon — AI Trading Agents**

| Name | Role |
|------|------|
| **Syed Taseer Abbas** | AI Engineer |

## 📄 License

MIT License — feel free to use and modify.

---

## 🔗 Links

- 🏆 [lablab.ai](https://lablab.ai)
- 🤖 [Anthropic Claude](https://anthropic.com)
- 📊 [CoinGecko API](https://coingecko.com/api)
- 😨 [Fear & Greed API](https://alternative.me/crypto/fear-and-greed-index)
``
