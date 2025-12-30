# 🧱 BrickBank

<div align="center">

![BrickBank Logo](https://img.shields.io/badge/🧱-BrickBank-f5cd2f?style=for-the-badge&labelColor=1a1a1a)

**The Ultimate LEGO Collection Manager & Price Tracker**

[![Python](https://img.shields.io/badge/Python-3.10+-3776ab?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.x-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [API Sources](#-api-sources) • [Roadmap](#-roadmap)

</div>

---

## 📖 Overview

BrickBank is a powerful LEGO set collection manager and price tracker built with Python Flask. It aggregates data from multiple sources to give you comprehensive information about any LEGO set, including real-time market prices, historical trends, and rarity scores.

Whether you're a collector tracking your investment, a reseller looking for deals, or just a LEGO enthusiast wanting to know what your sets are worth — BrickBank has you covered.

---

## ✨ Features

### 🔍 **Comprehensive Search**
- Search through **25,000+ LEGO sets** from 1949 to present
- Multi-word search support (e.g., "millennium falcon", "death star")
- Search by set number or name
- Instant local database queries — no waiting for API calls

### 📊 **Real-Time Price Tracking**
- **BrickLink Integration** — Sealed & used market prices (min/avg/max)
- **eBay Sold Listings** — Recent sale prices with condition tracking
- **Retail Prices** — MSRP from official LEGO stores
- **Amazon & Target** — Retail price tracking (coming soon)
- **Price History Charts** — Track price trends over years with interactive graphs

### 🏆 **Rarity Scoring System**
Sets are automatically scored based on:
- Age (older = rarer)
- Availability (retired sets score higher)
- Piece count (larger sets often more collectible)
- Market value vs. retail

| Tier | Score | Color |
|------|-------|-------|
| Ultra Rare | 90+ | 🟣 Purple |
| Rare | 70-89 | 🔴 Red |
| Uncommon | 50-69 | 🟠 Orange |
| Common | 30-49 | 🟢 Green |
| Very Common | <30 | ⚪ Gray |

### 📁 **Collection Management**
- Add sets to your personal collection
- Track purchase price, date, and condition
- Mark sets as owned, wanted, or for sale
- Calculate total collection value

### ❤️ **Favorites & Wishlist**
- Save sets to favorites for quick access
- Recently viewed history
- Persistent across sessions (localStorage)

### 🎨 **Modern Dark UI**
- Beautiful dark theme with LEGO-inspired accents
- Smooth animations and transitions
- Responsive design for all screen sizes
- JetBrains Mono typography

---

## 🚀 Installation

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/BrickBank.git
cd BrickBank

# Install dependencies
pip install -r [requirements.txt](http://_vscodecontentref_/0)

# Run the application
python [app.py](http://_vscodecontentref_/1)
