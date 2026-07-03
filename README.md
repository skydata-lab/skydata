[繁體中文](README.md) | [English](README_en.md)

# 🕯️ 光遇工具站 (Sky: Children of the Light Tools)

這是一個出於興趣製作的網頁工具集合，旨在為《光遇 (Sky: Children of the Light)》的玩家提供更簡潔、直觀的資訊，幫助大家輕鬆規劃遊戲中的資源花費（蠟燭、好感度等）。

🌍 **線上預覽 (Live Demo):** [點此前往你的網站](https://skydata-lab.github.io/skydata/)

---

## ✨ 主要功能 (Features)

### 1. 🕯️ 季節先祖解鎖計算器 (`spirit.html`)
* **資源試算：** 計算解鎖特定季節先祖物品所需的「季蠟」與「好感度」，並自動預估還需要多少天數才能完成。
* **多方案存檔：** 支援建立多套自定義解鎖方案（例如：主帳號、備用帳號、無季卡方案等），進度獨立儲存。
* **季節切換：** 支援透過選單快速切換不同季節的先祖資料。

### 2. 🤝 好友樹規劃器 (`friend.html`)
* **解鎖目標規劃：** 直觀展示好友樹各層級 (Tier) 節點，點擊即可計算解鎖至該節點所需消耗的總蠟燭與好感度門檻。
* **多好友管理：** 支援新增多位好友名稱，分別紀錄與不同好友的解鎖進度。
* **預覽模式：** 一鍵切換「全解鎖對比版」，方便查看完整的樹狀結構與物品外觀。

### 3. 全局特色
* 🌓 **黑暗模式 (Dark Mode)：** 支援亮色與暗色主題一鍵切換，保護眼睛。
* 💾 **無痕本地儲存：** 所有進度與方案皆自動儲存於瀏覽器的 `localStorage` 中，無需註冊登入即可保存進度。

---

## 📂 專案結構 (Project Structure)

本專案採用純前端技術 (Vanilla HTML/CSS/JS) 開發，無需額外安裝依賴即可運行。

```text
├── index.html            # 網站首頁與功能導覽
├── spirit.html           # 季節先祖計算器頁面
├── friend.html           # 好友樹規劃器頁面
└── data/                 # 存放計算器所需的 JSON 資料
    ├── spirits.json      # 季節先祖物品資料庫
    └── friend_tree.json  # 好友樹節點資料庫
```

⚠️免責聲明 (Disclaimer)

這是一個非官方的玩家自製專案，與 thatgamecompany 沒有任何從屬或合作關係。

(This is an unofficial fan-made project and is not affiliated with thatgamecompany.)