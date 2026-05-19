# 🖥️ Master Dashboard Switcher

An auto-switching dashboard container designed for monitoring stations. It seamlessly toggles between two live dashboards to maximize information display on a single screen.

## 🚀 Live Demo
👉 [Live Demo Link](https://nametempal.github.io/master-board/)

## 🛠️ Features
- **Auto-Switching**: Automatically toggles between Delivery and TV dashboards every 300 seconds (5 minutes).
- **Fullscreen Layout**: optimized for 100vw/100vh displays with no scrollbars or borders.
- **Interactive Countdown**: A subtle, glassmorphism-style timer at the bottom-right shows when the next switch will occur.
- **Manual Override**: Click the timer or press **Arrow Keys (Left/Right)** to switch between dashboards immediately.
- **Zero Configuration**: Built as a single, lightweight HTML file with vanilla CSS and JS.

## 📦 Dashboards Included
1. [Delivery Dashboard](https://nametempal.github.io/delivery-dashboard/)
2. [TV Dashboard](https://nametempal.github.io/tv-dashboard/)

## 🔧 Technical Details
- **Tech Stack**: HTML5, CSS3 (Vanilla), JavaScript (Vanilla).
- **Logic**: Uses dual iframes with `visibility` toggling to ensure the background dashboard stays loaded/active without refreshing during the switch.
- **Styling**: Absolute positioning with `z-index` control and backdrop-filter for the timer UI.

## 📝 Usage
Just open `index.html` in any modern web browser or navigate to the live URL. For best results, use **Fullscreen mode (F11)**.

---
Created by **nametempal**
