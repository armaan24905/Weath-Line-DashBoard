💰 Wealthline — AI-Powered Finance Tracker

## *Manage Money Smarter with AI* ✨

A premium, full-featured personal finance dashboard built with a luxury dark-mode aesthetic, real-time analytics, and AI-driven financial insights.

[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Chart.js](https://img.shields.io/badge/Charts-Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-C8A96A?style=for-the-badge)](#-license)

[🔗 Live Demo](https://armaan24905.github.io/Weath-Line-DashBoard/Wealth-Tracking-DashBoard.html) · [🐛 Report Bug](#) · [✨ Request Feature](#)

---

## 📖 Overview

**Wealthline** is a modern, AI-assisted personal finance tracker designed with the same design sensibility as **Apple, Linear, Stripe, and Notion**. It helps users track income and expenses, set budgets and savings goals, visualize spending patterns, and receive AI-generated financial insights — all wrapped in a premium glassmorphic, dark-luxury interface.

This project was built to demonstrate **end-to-end frontend engineering skill**: from interactive data visualization and state management to design systems, theming architecture, and UX polish — without relying on any external framework.

> 🎯 **Why this project stands out:** Every chart, insight, and prediction is powered by real logic (linear regression for forecasting, rule-based AI insight generation, live financial health scoring) rather than static mockups — built to *feel* like a production SaaS product.

---

## 🖼️ Preview

| Dashboard | Analytics | Prediction |
|---|---|---|
| *Screenshot 1*(https://github.com/armaan24905/Weath-Line-DashBoard/blob/59b6f328ae8883493431eef6c15e11c177d378c8/assets/Screenshot%201.png) | *Screenshot 2* | *Screenshot 3* |

> 💡 Replace the placeholders above with actual screenshots/GIFs from `/assets` once added.

---

## ✨ Key Features

### 🏠 Dashboard Overview
- 📊 Real-time balance, income, expense & investment summary cards
- 🧭 Animated **Financial Health Score** (0–100) calculated from live savings rate
- 🤖 **AI Insights panel** — dynamically generated spending analysis & recommendations
- 📈 Interactive cash-flow chart (6-month / 12-month toggle)
- 🍩 Category-wise spending breakdown (doughnut chart)

### 💸 Income & Expense Management
- ➕ Full **CRUD** — Add, Edit, Delete for both income & expenses
- 🔍 Live search and filtering (weekly / monthly / yearly)
- 🏷️ Color-coded category tags across 15+ categories

### 🎯 Budgets & Goals
- 📉 Per-category monthly budgets with live usage progress bars
- ⚠️ Automatic over-budget alerts
- 🏆 Savings goals with animated circular progress rings

### 🔮 AI-Style Prediction Engine
- 📐 Linear regression model projecting next 3 months of expenses
- 🎯 Confidence-scored forecasts with shaded confidence range
- 💹 Projected income, expense & savings estimates

### 📊 Analytics Suite
- Monthly income/expense trend charts
- Category-wise bar breakdown
- Cumulative savings growth (area chart)

### 🧾 Reports & Export
- 🖨️ One-click printable financial report
- 📤 CSV export of all transactions

### 🎨 Design System
- 🌓 **Dual theme engine** — Obsidian (dark) & Ivory (light), animated 300ms transitions
- 💎 Custom luxury color system (gold, emerald, rose, info-blue, violet — zero neon)
- 🌊 Signature **ambient "wealth ridge"** animated canvas background
- 🔔 Smart notification center (budget alerts, goal milestones, bill reminders)
- 📱 Fully responsive across desktop, tablet & mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Structure** | HTML5 (Semantic Markup) |
| **Styling** | CSS3 — Custom Properties (Design Tokens), Glassmorphism, Flexbox/Grid |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Data Visualization** | [Chart.js](https://www.chartjs.org/) |
| **Fonts** | System Font Stack (native OS typography for performance) |
| **Icons** | Custom hand-built SVG icon system |

> ⚙️ Built with **zero external frameworks** for the frontend logic — a deliberate choice to demonstrate strong fundamentals in vanilla JS, DOM manipulation, and CSS architecture before scaling to React/Next.js.

---

## 📂 Project Structure

```
wealthline/
│
├── Wealth-Tracking-DashBoard.html   # Single-file application (HTML + CSS + JS)
├── assets/                     # Screenshots, demo GIFs, preview images
├── README.md                   # You are here 📍
└── LICENSE
```

---

## 🚀 Getting Started

### Prerequisites
Just a modern web browser. No build tools, no npm install, no backend required to preview.

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/armaan24905/wealthline.git

# 2. Navigate into the project
cd wealthline

# 3. Open directly in your browser
open wealthline-dashboard.html   # macOS
start wealthline-dashboard.html  # Windows
```

That's it — no dependencies, no configuration. 🎉

---

## 🧠 How the "AI" Works

While this version doesn't call an external LLM API, the insight and prediction engine is genuinely **data-driven, not hardcoded**:

- 📊 **Financial Health Score** — derived live from savings rate + goal activity
- 💡 **Spending Insights** — generated by analyzing the highest-spend category, recurring subscriptions, and savings percentage against live transaction data
- 📈 **Expense Prediction** — uses **linear regression** over the last 6 months of transaction history to project the next 3 months, with a calculated confidence percentage

This architecture is designed to plug directly into a real OpenAI/LLM API call in a future backend iteration — see [Roadmap](#-roadmap) below.

---

## 🗺️ Roadmap

- [ ] 🔐 Authentication (JWT + Google OAuth + OTP verification)
- [ ] 🗄️ Backend integration — Node.js, Express, MongoDB
- [ ] 🤖 Live OpenAI API integration for natural-language financial advice
- [ ] 📱 PWA support with offline mode
- [ ] 🧾 OCR-based receipt scanning
- [ ] 🎙️ Voice-based expense entry
- [ ] 🌍 Multi-currency conversion support

---

## 🙋‍♂️ About the Developer

**H. Armaan Saad**  
🎓 B.Tech in Artificial Intelligence & Data Science.

Passionate about building products at the intersection of **AI, clean engineering, and premium design** — with hands-on experience across full-stack development, data science, and applied ML projects.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/armaan24905)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/armaan-saad-120251306)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](../../issues) or open a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

### ⭐ If you found this project impressive, consider giving it a star!

*Built with 💛 and a lot of attention to detail.*

