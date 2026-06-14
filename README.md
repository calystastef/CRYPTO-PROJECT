# Crypto Tracker

A real-time cryptocurrency price tracker built with React and Vite. Browse the top 100 coins by market cap, search and sort them, then click into any coin for a detailed view with a 7-day price chart and market stats.

## live demo 
[Try it live] (https://crypto-project-puce-omega.vercel.app/)

## tech stack

- React 19
- React Router 7
- Recharts
- Vite
- JavaScript (ES6+)
- CSS

## features

- Live prices and market data for the top 100 cryptocurrencies
- Search by coin name or ticker symbol
- Sort by rank, name, price, 24h change, or market cap
- Toggle between grid and list view
- Coin detail page with:
  - 7-day interactive price chart
  - 24h high / low
  - Market cap, 24h volume, circulating supply, total supply

## project structure

```
src/
├── api/
│   └── coinGecko.js       # API calls (market list, coin detail, chart data)
├── components/
│   └── CryptoCard.jsx     # Card used in the home grid/list
├── pages/
│   ├── Home.jsx           # Landing page — search, sort, and browse coins
│   └── CoinDetail.jsx     # Detail page — chart and market stats for one coin
├── utils/
│   └── formatter.js       # Price and market cap formatting helpers
└── App.jsx                # Router setup
```

## what I learned

- Fetching and displaying data from a public REST API
- React Router for client-side navigation between pages
- Building interactive charts with Recharts
- Managing search, filter, and sort state across components

## credits

Data provided by the [CoinGecko API](https://www.coingecko.com/en/api) — free public tier, no API key required.
