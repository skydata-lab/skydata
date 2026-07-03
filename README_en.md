[繁體中文](README.md) | [English](README_en.md)

# 🕯️ Sky: Children of the Light Tools

This is a hobbyist web tool collection designed to provide a clean and intuitive information hub for "Sky: Children of the Light" players. It helps everyone easily plan their in-game resource expenditures (candles, hearts, ascended candles, etc.).

🌍 **Live Demo:** [Click here to visit the site](https://skydata-lab.github.io/skydata/)

---

## ✨ Features

### 1. 🕯️ Seasonal Spirit Unlock Calculator (`spirit.html`)
* **Resource Calculation:** Calculates the "Seasonal Candles" and "Hearts/Ascended Candles" required to unlock specific seasonal spirit items, and automatically estimates the number of days needed to complete your goal.
* **Multi-Plan Saves:** Supports creating multiple custom unlock plans (e.g., main account, alt account, no-adventure-pass plan). Progress for each plan is saved independently.
* **Season Switching:** Quickly switch between different seasonal spirits' data via the dropdown menu.

### 2. 🤝 Friend Tree Planner (`friend.html`)
* **Unlock Goal Planning:** Intuitively displays the nodes for each tier in the friend tree. Click a node to calculate the total candles and thresholds required to unlock up to that point.
* **Multi-Friend Management:** Supports adding multiple friend names, allowing you to separately track your unlock progress with different friends.
* **Preview Mode:** A one-click toggle to a "Full Unlock Comparison" view, making it easy to see the complete tree structure and item appearances.

### 3. 🌐 Global Features
* 🌓 **Dark Mode:** One-click toggle between light and dark themes to reduce eye strain.
* 💾 **Local Storage:** All progress and plans are automatically saved in your browser's `localStorage`. No registration or login is required to save your data!

---

## 📂 Project Structure

This project is developed using pure front-end technologies (Vanilla HTML/CSS/JS). It can be run directly without installing any additional dependencies.

```text
├── index.html            # Website homepage and navigation
├── spirit.html           # Seasonal spirit calculator page
├── friend.html           # Friend tree planner page
└── data/                 # Directory for JSON data used by the calculators
    ├── spirits.json      # Seasonal spirit items database
    └── friend_tree.json  # Friend tree nodes database
```

⚠️ Disclaimer
This is an unofficial fan-made project and is not affiliated with thatgamecompany.