# 🧠 AI Trade Predictor — The Future of Intelligent Crypto Trading

> Powered by real-time sentiment, on-chain intelligence, and machine learning — because alpha shouldn't be a secret.

---

## 🚀 Overview

**AI Trade Predictor** is a next-generation crypto analytics tool that fuses **natural language sentiment** from Twitter, Reddit, Telegram with **on-chain trading metrics** to produce **AI-driven BUY/SELL/HOLD signals**.

Designed for traders, degens, and research analysts who want **fast, actionable insights** in a rapidly evolving market — **before the crowd catches on.**

Whether you're hunting early entries, avoiding exit traps, or just want smarter alerts, this bot is your tactical edge.

---

## ⚙️ Core Features

| Feature                          | Description |
|----------------------------------|-------------|
| 📡 **Real-Time Sentiment Engine** | Extracts public mood from social platforms using NLP (VADER) |
| 🧬 **On-Chain Intelligence**      | Tracks price, volume, whale transactions and more |
| 🤖 **AI-Powered Signal Generator**| Combines sentiment + on-chain data to output confidence-based trading signals |
| 🧪 **Backtested Signal Logic**    | Basic model trained on mock sets to simulate directional accuracy |
| 🖥️ **Command Line Interface**     | Lightweight interface for instant predictions |
| 💬 **Explanations per Signal**    | Transparent logic explaining why each prediction was made |
| 🔌 **Telegram Bot Ready**         | Modular architecture built to plug into Telegram automation |

---

## 🧠 How It Works

1. **Scrape Twitter/X and crypto Telegram chatter** about trending tokens.
2. **Score sentiment** using VADER (Very fast for real-time NLP).
3. **Fetch token-specific metrics** such as 24H price change, volume change, and whale tx count.
4. **Run predictions** using a trained `RandomForestClassifier` or `XGBoost` model.
5. **Display clean, human-readable results** in the CLI or Telegram interface.

---

## 📦 Folder Structure

