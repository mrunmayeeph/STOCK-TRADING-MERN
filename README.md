
# 📈 Stock Trading Web App

A full-stack stock trading platform where users can sign up, manage their portfolios, buy/sell stocks, and view order history. The UI is inspired by Bloomberg, featuring dark mode and a sleek financial dashboard look.

## 🔥 Features

- 🧾 **User Authentication** – Sign up, log in, and role-based account creation.
- 💼 **Stock Trading** – Buy and sell stocks with real-time updates to your balance and holdings.
- 📊 **Portfolio Management** – Track your owned stocks and order history.
- 📰 **News Section** – Live market-related news to stay informed.
- 📂 **Order History** – Organized display of intraday and delivery orders.
- 💡 **Responsive Design** – Optimized for various screen sizes.
- 🎨 **Dark Mode UI** – Financial dashboard vibe with stylish component layouts.

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Axios
- React Icons
- CSS (custom styling, inspired by Bloomberg UI)

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose ODM)

## 📁 Folder Structure

```
Stocks-Trading-MERN
│
├── README.md
│
├── client
│   ├── README.md
│   ├── package.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   └── src
│       ├── App.css
│       ├── App.js
│       ├── App.test.js
│       ├── index.css
│       ├── index.js
│       ├── reportWebVitals.js
│       ├── setupTests.js
│       ├── assets
│       │   ├── about1.jpg
│       │   ├── about2.jpg
│       │   └── home-hero-img.png
│       ├── components
│       │   ├── Login.jsx
│       │   ├── Navbar.jsx
│       │   └── Register.jsx
│       ├── context
│       │   └── GeneralContext.jsx
│       ├── pages
│       │   ├── Admin.jsx
│       │   ├── AdminStockChart.jsx
│       │   ├── AllOrders.jsx
│       │   ├── AllTransactions.jsx
│       │   ├── History.jsx
│       │   ├── Home.jsx
│       │   ├── Landing.jsx
│       │   ├── News.jsx
│       │   ├── Portfolio.jsx
│       │   ├── Profile.jsx
│       │   ├── StockChart.jsx
│       │   └── Users.jsx
│       ├── RouteProtectors
│       │   ├── AuthProtector.jsx
│       │   └── LoginProtector.jsx
│       └── styles
│           ├── Admin.css
│           ├── AdminStockChart.css
│           ├── AllOrders.css
│           ├── AllTransactions.css
│           ├── History.css
│           ├── Home.css
│           ├── Landing.css
│           ├── Navbar.css
│           ├── news.css
│           ├── Portfolio.css
│           ├── Profile.css
│           ├── StockChart.css
│           └── Users.css
│
└── server
    ├── index.js
    ├── package.json
    └── Schema.js```
