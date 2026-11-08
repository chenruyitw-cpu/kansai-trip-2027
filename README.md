# 🇯🇵 2027 關西 8 天 7 夜熱血自由行・7 人實戰作戰手冊與互動導航平台

> 一套專為 7 人日本關西（大阪・京都・宇治・嵐山）自由行打造的**全方位互動式旅遊作戰手冊與隨身 Web App**。

[![Cloudflare Pages](https://img.shields.io/badge/Deployed%20with-Cloudflare%20Pages-f38020?logo=cloudflare)](https://pages.cloudflare.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PWA Ready](https://img.shields.io/badge/Mobile-PWA%20Ready-green.svg)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

---

## 📌 專案緣起與目標 (Project Background)

跳脫傳統枯燥死板的待辦事項與旅行清單，本專案將 2027 年 1 月即將啟程的 **7 位成人 8 天 7 夜關西京阪深度自由行**，完整轉化為現代化、具備離線操作能力與高實戰防呆價值的**互動式 Web 手冊**。

本網站核心策略：
- **不買任何昂貴 Pass**，全員使用 iPhone **Apple Pay ICOCA / Suica** 隨刷隨搭。
- **全程兩大包棟 Airbnb**（大阪千鳥橋洋房 3 晚 ＋ 京都伏見私人半露天檜木風呂湯屋 4 晚）。
- **實地月台與列車實拍照防呆**，徹底根除大車站迷航問題。

---

## ✨ 網站核心特色與操作指南 (Core Features)

1. **📖 內建新手教學與操作解說 (Built-in User Guide)**
   - 頂部導航列設有「📖 網站使用解說」按鈕與指引橫幅。
   - 點擊即可開啟詳細的 4 大功能教學彈窗，說明如何利用本平台查行程、看月台、勾選清單與離線使用。
2. **🗺️ 8 天實戰極速時間表與月台車資矩陣**
   - 包含 Day 1 至 Day 8 完整時程安排、景點停留時間、Google Maps 路線連結與乘車費用。
   - 設有懸浮「Day 1 ~ Day 8」導覽按鈕，一鍵直達當日作戰行程。
3. **🚉 實體車站月台與車輛圖鑑 (Transit & Platform Visualizer)**
   - 內建 16 張真實車站月台（關西機場、難波、西九條、大阪、伏見稻荷等）與列車外觀（HARUKA、南海機場急行、阪神電車、JR 323/223/221 系等）。
   - 旅途中直接比對手機畫面，杜絕搭錯月台或坐錯車種。
4. **🧳 互動打包行李檢查表 (LocalStorage Auto-Sync)**
   - 支援即時點擊勾選。
   - 勾選進度**自動同步儲存至瀏覽器（LocalStorage）**，即使離線、關閉瀏覽器或重新整理，打勾紀錄永不遺失。
5. **🖨️ 專業 A4 列印排版與手機轉存 PDF**
   - 針對列印介面深度優化，點擊「🖨️ 列印 / 轉存 PDF」即可自動隱藏雜亂按鈕，格式精準適配 A4 規格。
6. **📱 手機主畫面 App 化 (PWA Ready)**
   - 支援在 iPhone（Safari 分享 > 加入主畫面）與 Android（Chrome > 加到主畫面），形成獨立圖示，如同原生 App 般在旅途中隨點隨用。

---

## 🚀 本地即時預覽 (Local Preview)

本專案採用極致輕量化、零依賴架構：
1. 下載或複製本專案資料夾。
2. 直接雙擊開啟 `index.html`，即可在任何瀏覽器中體驗完整互動功能與照片瀏覽。

---

## 🌐 雲端部署指南 (Cloudflare Pages Deployment)

1. 將本專案（`index.html`、`images/` 資料夾與 `README.md`）上傳至 GitHub 儲存庫。
2. 登入 [Cloudflare Dashboard](https://dash.cloudflare.com/) 進入 **Workers & Pages**。
3. 點選 **Create application** > **Pages** > **Connect to Git**。
4. 選擇你的 GitHub 儲存庫（如 `kansai-travel-handbook`）：
   - **Framework preset**: `None`
   - **Build command**: *(留空)*
   - **Build output directory**: `/` (或留空)
5. 點擊 **Save and Deploy**，即可在幾秒內獲得專屬的 `https://<your-project>.pages.dev` 網址！

---

## 📅 行程精華一覽
- **Day 1**：抵達關西・難波大集合・梅田夕陽百萬夜景
- **Day 2**：USJ 日本環球影城・瑪利歐園區狂歡
- **Day 3**：大阪城平次巡禮・和牛燒肉・日本橋動漫・公道卡丁車巡航・道頓堀
- **Day 4**：移防京都・鋼彈基地・teamLab Biovortex 光影漩渦
- **Day 5**：和服變裝日・花見小路・清水寺・先斗町鴨川
- **Day 6**：嵐山竹林幽境・天龍寺・金閣寺・四條河原町
- **Day 7**：清晨獨享千本鳥居・宇治抹茶・和牛壽喜燒派對
- **Day 8**：特急 HARUKA 直達關西機場・免稅採買返台
