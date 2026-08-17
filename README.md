# MoonTea 月輪茶棧

「月輪茶棧」形象網站 — 一個結合便利商店與飲料店概念的品牌介紹單頁式網站，使用 HTML / CSS / jQuery 搭配 Bootstrap 4 製作，並整合 Google Maps 顯示門市位置。

## 專案簡介

月輪茶棧將便利商店機能與飲料店服務結合，提供大眾化飲茶及客製化需求（甜度、冰度、加料），同時提供廁所、哺乳室、繳費等便利服務。本專案為其品牌宣傳網站，內容涵蓋最新消息、門市地點、商品分類、品牌介紹與線上留言等區塊。

## 功能區塊

- **首頁輪播** — 品牌形象輪播圖與標語
- **最新消息 (News)** — DM 下載、活動、徵才、新品等最新消息卡片
- **門市地點 (Store)** — 各分店電話 / 地址列表，點選後於 Google Maps 顯示對應位置
- **商品專區** — 清涼飲品、活力咖啡、綜合果汁、現泡茶飲四大分類
- **關於月輪 (About)** — 品牌理念、經營理念、加盟資訊（分頁籤切換）
- **聯絡我們 (Contact Us)** — 表單留言（姓名、信箱、住址、意見），送出前進行必填與特殊字元檢查
- **頁尾** — 公司資訊與社群媒體連結

網頁並依滾動位置為各區塊加上淡入 / 縮放等進場動畫效果。

## 技術棧

- HTML5 / CSS3
- [Bootstrap 4](https://getbootstrap.com/)（版面、表單、分頁籤、輪播元件）
- [jQuery 3.3.1](https://jquery.com/)（互動效果、滾動事件）
- [Font Awesome](https://fontawesome.com/)（圖示）
- [animate.css](https://animate.style/)（動畫效果）
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript)（門市地圖）

## 專案結構

```
MoonTea/
├── index.html          # 主頁面
├── CSS/                # 樣式檔案（Bootstrap、Font Awesome、animate.css、自訂樣式）
├── JS/                 # 腳本檔案（jQuery、自訂互動腳本）
├── HTML/                # 頁面備份 / 草稿
├── image/               # 網站圖片素材
├── package.json
└── README.md
```

## 使用方式

本專案為純前端靜態網站，無需建置流程，直接以瀏覽器開啟 `index.html` 即可預覽，或使用簡易的本機伺服器啟動：

```bash
# 使用 Python 內建伺服器
python3 -m http.server 8080

# 或使用 Node.js 的 http-server
npx http-server .
```

啟動後於瀏覽器開啟 `http://localhost:8080` 瀏覽。

> 門市地圖功能需要有效的 Google Maps API 金鑰，請於 `index.html` 中替換 `key` 參數為自己的金鑰。

## 授權

僅供學習與展示用途。網站內容與部分圖片參考自怡客咖啡官網。
