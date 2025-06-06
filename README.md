# 📈 Stock Screener

A simple and responsive stock screener built with React that integrates with TradingView's screener API to display trending and high-performing Indian stocks based on selected criteria.

## 🚀 Live Demo

Check out the live demo here: [Stock Screener](https://sreesri4.github.io/StockScreener)

## 🧰 Features

- Dropdown filters for:
  - 52 Week High
  - Volume Buzzers
  - 1 Month High
  - 100% Up in a Year
- POST request to TradingView screener API (`[https://scanner.tradingview.com/india/scan](https://scanner.tradingview.com/india/scan?label-product=popup-screener-stock)`)
- Payloads for each dropdown maintained under server/screener-payload.ts
- Displays filtered stock data in a responsive table
- Sortable columns (e.g., Symbol, Price, Volume, etc.)
- Integrated TradingView advanced chart link for symbol

## 📦 Tech Stack

- React + Vite
- Tailwind CSS (or any styling method used)
- TradingView Widget
- Axios (for API calls)

## 📂 Folder Structure
StockScreener/
├── .github/
│   └── workflows/
├── attached_assets/
├── client/
    └── src
        └── components
        └──lib
        └──pages
        └──main.tsx
    └──index.html
├── public/
├── server/
    └──routes.ts
    └──screener-payload.ts
    └──vites.ts
    └──index.ts
├── shared/
    └──schema.ts
├── .gitignore
├── .replit
├── components.json
├── drizzle.config.ts
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts

