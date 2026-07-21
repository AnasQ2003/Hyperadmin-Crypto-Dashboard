<div align="center">

# ⚡ HyperAdmin — Crypto Dashboard

### *Premium Cryptocurrency Portfolio Management & Trading Simulation Interface*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384.svg?style=flat-square&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.0-528DD7.svg?style=flat-square&logo=fontawesome&logoColor=white)](https://fontawesome.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

> **HyperAdmin** is a high-fidelity, single-page application prototype designed to simulate a modern cryptocurrency portfolio dashboard. Engineered with a premium **glassmorphic dark UI**, dynamic Chart.js visualizations, real-time simulated price ticks, and full client-side session persistence.

### 🌐 [**Live Demo → anasq2003.github.io/Hyperadmin-Crypto-Dashboard**](https://hyperadmincryptodashboard.netlify.app/)

</div>

---

## ✨ Features

| Category | Feature | Description |
|---|---|---|
| 🔐 **Authentication** | **Client-Side Session Lock** | Glassmorphic login portal with persistent authentication states powered by `localStorage` |
| 📊 **Dashboard** | **Holdings Overview** | Real-time valuation cards for portfolio balance ($USD), 24h change %, and BTC/ETH positions |
| | **Bitcoin Line Chart** | Interactive 30-day historical chart with 1D, 1W, 1M, 1Y, and ALL time scales |
| | **Simulated Live Market** | Live price tickers, dynamic Time & Sales order logs, and overall Market Overview tables |
| | **Trading Terminal** | Mock trading desk widget enabling instant BUY/SELL calculations with fee estimates |
| 💼 **Wallet** | **Balance Ledger** | Portfolio breakdown showing quantities, values, and quick trading shortcuts for major tokens |
| | **Asset Allocation** | Beautiful doughnut chart illustrating percentage distribution of asset holding values |
| | **Funds Transfer Modals** | Simulated deposit address generators (with copy-to-clipboard) and withdrawal forms |
| 🔄 **Transactions** | **History Ledger** | Dynamic record of past orders, deposits, and withdrawals with color-coded status badges |
| 📈 **Portfolio** | **Historical Performance** | Detailed line chart tracking multi-month returns alongside analytical metrics tables |
| 📰 **Market Data** | **Market Capitalization** | Comparative horizontal bar chart for top-tier coins, plus Top Gainers and Top Losers tables |
| ⚙️ **Control Panel** | **Settings & Preferences** | Editable profile info forms, notification checkbox toggles, and functional 2FA switches |

---

## 🖥️ Tech Stack

| Component | Technology | Purpose |
|---|---|---|
| **Core Layout** | **HTML5** | Semantic layout structure, sidebar menus, and dialog controls |
| **Theme & Design** | **CSS3** | Premium glassmorphism effects (`backdrop-filter`), CSS Grid/Flex, custom variables |
| **Interactivity** | **Vanilla JS** | Client-side routing, modular overlay triggers, real-time data generators |
| **Data Graphs** | **Chart.js** | Line charts, donut allocations, and vertical bar representations |
| **Session States**| **LocalStorage** | Session caching for login credentials, notification params, and 2FA states |

---

## 🚀 Getting Started

```bash
git clone https://github.com/AnasQ2003/Hyperadmin-Crypto-Dashboard.git
cd Hyperadmin-Crypto-Dashboard
start login.html      # Windows
open login.html       # macOS
```

Or run a local server:
```bash
python -m http.server 8000
# http://localhost:8000/login.html
```

---

## 📂 Project Structure

```
Hyperadmin-Crypto-Dashboard/
├── login.html    # 🔐 Secure login portal
├── index.html    # 💻 Main SPA (dashboard, wallet, transactions, portfolio, market, settings)
├── e1.png        # Login screen
├── e2.png        # Dashboard primary page
├── e3.png        # Time & Sales + Market Overview
├── e4.png        # Notifications dropdown
├── e5.png        # Wallet balances + donut chart
├── e6.png        # Deposit modal
├── e7.png        # Withdraw modal
├── e8.png        # Transactions ledger
├── e9.png        # Portfolio performance chart
├── e10.png       # Settings — account details
├── e11.png       # Settings — alert thresholds
├── e12.png       # Markets — Market Cap chart
├── e13.png       # Markets — 24h Volume chart
├── e14.png       # Chart hover tooltip
└── README.md
```

---

## 📸 Screen Preview Gallery

### 🔐 Authentication & Login

**Login Portal**
![Login Card](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e1.png)

---

**Dashboard Notifications**
![Active Notifications Dropdown](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e4.png)

---

### 📈 Core Dashboard & Charts

**Primary Overview**
![Primary Dashboard](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e2.png)

---

**Market Data Feeds**
![Time and Sales scrolled](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e3.png)

---

### 💼 Portfolio & Wallets

**Wallet Balances & Allocation**
![Wallet Balances and Donut](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e5.png)

---

**Historical Performance**
![Portfolio performance over time](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e9.png)

---

### 🔄 Funds Transfers

**Deposit Modal**
![Deposit Funds Dialog](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e6.png)

---

**Withdraw Modal**
![Withdraw Funds Dialog](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e7.png)

---

### 📑 Transactions & Market Analytics

**Historic Ledger**
![Transactions Record table](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e8.png)

---

**Market Capitalization**
![Market Cap bar charts](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e12.png)

---

### 📊 Trading Volumes & Interactive Elements

**24h Volume Charts**
![Volume Charts scrolled](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e13.png)

---

**Line Chart Hover Details**
![Hover tooltip demo](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e14.png)

---

### ⚙️ Account Management

**Account Settings**
![Profile Editing Form](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e10.png)

---

**Alert Rules & Security**
![Threshold rules config](https://raw.githubusercontent.com/AnasQ2003/Hyperadmin-Crypto-Dashboard/main/e11.png)

---

## 🔄 Simulated Logic Architecture

```javascript
function simulatePriceTicks() {
  setInterval(() => {
    assets.forEach(asset => {
      const changePercent = (Math.random() - 0.5) * 0.4;
      asset.price *= (1 + changePercent / 100);
      updateDashboardDOM(asset);
    });
  }, 4000);
}
```

```javascript
new Chart(ctx, {
  type: 'doughnut',
  data: {
    labels: ['Bitcoin', 'Ethereum', 'Litecoin', 'USDC'],
    datasets: [{ data: [51.2, 30.9, 5.1, 12.8], backgroundColor: ['#2563eb', '#3b82f6', '#60a5fa', '#10b981'] }]
  },
  options: { responsive: true, cutout: '70%' }
});
```

---

## 🤝 Contributing

1. Fork the project.
2. Create your Feature Branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'feat: add AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request.

---

## 📄 License

```
MIT License

Copyright (c) Hyperadmin-Crypto-Dashboard --- 2026 AnasQ2003

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 👨‍💻 Author

**Anas Ahmed Qureshi** — [@AnasQ2003](https://github.com/AnasQ2003)

---

<div align="center">
