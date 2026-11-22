# Felicia Studio｜平面設計・品牌識別 Landing Page

這是一個為獨立平面設計師 Felicia 打造的個人品牌形象網站（Landing Page），以溫暖、有質感的森林綠與暖陽黃配色，展示品牌識別、包裝與編輯設計作品。

## 網站功能

- **固定導覽列**：捲動頁面時自動切換為半透明毛玻璃背景，可快速跳轉至「作品」、「服務」與「聯繫」區塊。
- **Hero 主視覺區**：主標語「為溫柔的品牌，設計有溫度的視覺語言」，並提供「與我聯繫」與「看作品」行動按鈕。
- **精選作品**：展示「森日咖啡」、「葉語植栽選物」、「慢旅・步行誌」等案例。
- **聯繫區塊**：引導訪客與設計師聯絡合作。
- **頁尾快速連結**：包含作品、聯繫與「回到頂端」連結。
- **動態效果**：淡入與捲動顯示（reveal）動畫、平滑捲動；並支援 `prefers-reduced-motion`，為偏好減少動態的使用者關閉動畫。
- **RWD 響應式設計**：針對平板（≤ 960px）與手機（≤ 640px）優化版面，在各種螢幕尺寸都能舒適瀏覽。

## 使用技術

- **HTML5**：語意化標籤（`nav`、`section`、`footer` 等）與無障礙屬性（`aria-label`）。
- **CSS3**：
  - CSS 自訂屬性（變數）統一管理色彩、字型與圓角
  - Flexbox / Grid 版面配置
  - `@media` 媒體查詢實作 RWD
  - 漸層背景、`backdrop-filter` 毛玻璃效果、SVG 顆粒質感
  - CSS 轉場與動畫
- **Google Fonts**：Inter、Cormorant Garamond、Noto Sans TC
- 少量原生 JavaScript：處理導覽列捲動狀態與捲動顯示動畫（無任何框架或建置工具）

## 如何用瀏覽器開啟

本專案為純靜態網頁，不需要安裝任何套件或伺服器。

**方法一：直接開啟檔案**

1. 下載或 clone 本專案：
   ```bash
   git clone https://github.com/Felicia-chou/claude-lab.git
   ```
2. 進入 `claude-lab` 資料夾，對 `index.html` 按兩下，即會以預設瀏覽器開啟。
   - 或在 `index.html` 上按右鍵 →「開啟方式」→ 選擇 Chrome、Edge、Firefox 等瀏覽器。

**方法二：使用 VS Code Live Server（選用）**

1. 在 VS Code 安裝「Live Server」擴充功能。
2. 開啟專案資料夾，於 `index.html` 按右鍵選擇「Open with Live Server」，修改後即可自動重新整理。

> 提示：字型由 Google Fonts 載入，請在連網狀態下開啟以獲得最佳顯示效果。

## 專案結構

```
claude-lab/
├── index.html   # Landing Page 主頁面（HTML + 內嵌 CSS / JS）
├── note.txt     # 練習用筆記
└── README.md    # 專案說明文件
```
