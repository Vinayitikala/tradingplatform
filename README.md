# 🚀 CryptoSage

> A Full Stack Cryptocurrency Trading Simulation Platform

---

## 📖 Overview

CryptoSage is a full-stack web application that provides a realistic cryptocurrency trading simulation environment. Users can buy and sell cryptocurrencies using virtual money, manage wallets, track portfolios, monitor live market prices, and interact with an AI-powered chatbot for crypto-related guidance. The platform helps beginners understand cryptocurrency trading without financial risk.

---

## ✨ Features

- 🔐 Secure User Authentication
- 💰 Virtual Wallet Management
- 📈 Real-Time Cryptocurrency Prices
- 🛒 Buy Cryptocurrencies
- 💸 Sell Cryptocurrencies
- 📊 Portfolio Tracking
- 📜 Transaction History
- 🤖 AI Chatbot (Gemini)
- 💵 Deposit & Withdraw Funds
- 🔄 Wallet-to-Wallet Transfer

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Spring Boot
- Spring Security
- Spring Data JPA

### Database
- MySQL

### APIs
- CoinGecko API
- Gemini AI API

### Tools
- Git
- GitHub
- Maven

---

## 🏗 System Architecture

```
              User
                │
                ▼
      React Frontend
                │
                ▼
      Spring Boot Backend
        │              │
        │              ├── Gemini AI
        │
        ├── CoinGecko API
        │
        ▼
      MySQL Database
```

---

## 📂 Project Structure

```
CryptoSage
│
├── frontend
├── backend
├── database
├── screenshots
└── README.md
```

---

## ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/CryptoSage.git
```

### Backend

```bash
cd backend
mvn spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

```
MYSQL_URL=

MYSQL_USERNAME=

MYSQL_PASSWORD=

JWT_SECRET=

COINGECKO_API_KEY=

GEMINI_API_KEY=
```

---

## 📊 Database Tables

- Users
- Wallet
- Portfolio
- Transactions
- Coins

---

## 🔗 REST APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/auth/register | Register User |
| POST | /api/auth/login | Login |
| GET | /api/coins | Live Coins |
| POST | /api/trade/buy | Buy Coin |
| POST | /api/trade/sell | Sell Coin |
| GET | /api/wallet | Wallet |
| GET | /api/portfolio | Portfolio |

---

## 🚀 Future Scope

- Mobile Application
- AI Trading Recommendations
- Leaderboards
- Price Alerts
- Advanced Portfolio Analytics
- Multi-language Support

---

## 👥 Team

- Vinay Itikala
- V kishore
- A Nikhil

---

## 🎓 Guide

Dr Shanti Makka
Assistant Professor

Department of Computer Science & Engineering (Data Science)

---


---

## ⭐ Acknowledgement

We sincerely thank our project guide, faculty members, and the Department of Computer Science and Engineering (Data Science) for their continuous support and guidance throughout the development of this project.

---
