<div align="center">

# ⚡ FXPulse — Real-Time Currency Converter & FX Intelligence Terminal

**A modern, institutional-grade web application for live currency conversion, historical exchange rate analytics, and multi-currency tracking.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-10B981?style=for-the-badge&logo=githubpages&logoColor=white)](https://minahil-cs.github.io/currency-converter/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 📖 Overview

**FXPulse** goes beyond basic currency calculators by combining real-time exchange rate APIs with interactive financial analytics in a responsive, dark-mode terminal interface. Built with zero heavy frontend frameworks, it delivers fast performance, resilient offline fallback protection, and clean UI/UX engineered for instant financial decision-making.

---

## ✨ Key Features

- **⚡ Real-Time FX Conversion Engine**
  - Fetches live global exchange rates via `open.er-api.com` with instant calculation, inverse rate display, and manual refresh synchronization.
  - Built-in resilient fallback mechanism ensures the terminal remains functional even during network interruptions.
- **📊 Interactive Historical Trend Analytics (7D / 30D / 90D)**
  - Custom-built responsive HTML5 Canvas line chart with interactive hover crosshairs, dynamic tooltips, and period **High / Low / Average** rate metrics.
  - Integrates real historical time-series data via the Frankfurter API with anchored market synthesis for extended currency pairs (such as PKR, AED, and SAR).
- **🏦 FX Spread & Bank Fee Simulator**
  - Models real-world interbank vs. retail bank/transfer provider markups (`0%` Interbank up to `5%` Bank Wire) to show exact net received amounts and hidden conversion costs.
- **🌐 Live Multi-Currency Board**
  - Simultaneously converts your input amount across customizable global currencies (USD, EUR, GBP, PKR, AED, JPY, CAD, AUD, etc.) in real time.
- **🔍 Searchable Currency Selector & Quick Presets**
  - Fast modal search across 24+ major global currencies by code, country, or currency name, paired with quick amount preset pills and one-click clipboard copy.
- **💾 Persistent Conversion History**
  - Automatically logs recent conversions in `localStorage` with timestamps and one-click state restoration.

---

## 🛠️ Tech Stack & APIs

| Category | Technologies Used |
| :--- | :--- |
| **Frontend Markup & Styling** | Semantic HTML5, Tailwind CSS (CDN), Custom CSS Scrollbars & Animations |
| **Core Logic & Graphics** | Vanilla JavaScript (ES6+), HTML5 `<canvas>` API for charting |
| **Typography & Icons** | Google Fonts (`Inter` & `JetBrains Mono`), Lucide Icons |
| **Exchange Rate APIs** | ExchangeRate-API (`open.er-api.com`), Frankfurter Historical FX API |
| **State Persistence** | Browser `localStorage` API |

---

## 📂 Project Structure

```text
currency-converter/
├── index.html        # Complete self-contained application (UI, Styles, Chart Engine & API Logic)
└── README.md         # Project documentation
````
🚀 Getting Started (Local Setup)
Clone the repository:

Bash
git clone [https://github.com/Minahil-CS/currency-converter.git](https://github.com/Minahil-CS/currency-converter.git)
Navigate into the project directory:

Bash
cd currency-converter
Run the application:

Open index.html directly in any modern web browser, or

Use the Live Server extension in VS Code for local development.

👩‍💻 Author
Minahil Fatima

GitHub: @Minahil-CS
