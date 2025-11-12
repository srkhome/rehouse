# 危老重建名單收集網站（淺藍主題＋60分鐘版）

這是一個三頁式行銷名單收集網站，用於宣傳「危老重建」免費說明會。  
網站風格為明亮淺藍主題，採用 HTML + CSS + JavaScript 製作，無需伺服器即可在 GitHub Pages 上運作。  

---

## 📄 網站結構

| 頁面 | 檔名 | 功能說明 |
|------|------|-----------|
| 首頁 | `index.html` | 活動介紹＋引導至名單填寫頁（含「📊 資料後台登入」連結） |
| 表單頁 | `form.html` | 使用者填寫姓名與 Email，資料會存入 LocalStorage |
| 感謝頁 | `thanks.html` | 顯示活動資訊、嵌入 YouTube 影片與 LINE 報名按鈕 |
| 後台 | `admin.html` | 管理員登入後可查看名單、下載 CSV、清空測試資料 |

---

## 🎨 網站特色

- **明亮淺藍主題**：主色 `#f0f7ff`、按鈕藍 `#007bff`、輔色青 `#00bcd4`。  
- **響應式設計**：支援手機與桌機顯示。  
- **模擬名單儲存**：以 `LocalStorage` 暫存資料，方便前端展示或測試。  
- **安全後台登入**：  
  - 帳號：`ueue31@gmail.com`  
  - 密碼：`87654321`  
- **一鍵下載名單**：可匯出成 `leads.csv` 供後續整理。  
- **報名整合**：`P3` 內含 LINE 報名按鈕，連結至 `https://line.me/ti/p/40LmfznrLG`。  
- **影片內嵌**：說明會影片嵌入 YouTube。  

---

## 🧭 使用方式

1. **下載本專案**
   ```bash
   git clone https://github.com/yourname/危老重建-名單網站.git
   cd 危老重建-名單網站
   ```
   或直接上傳 `危老重建_名單收集網站_淺藍版.zip` 至 GitHub。

2. **上傳到 GitHub Pages**
   - 進入專案設定 → Pages → Branch 選擇 `main` 與 `/ (root)`。  
   - 等待約 1 分鐘後，網站即可線上使用。  

3. **查看名單**
   - 前往首頁或感謝頁右上角點擊「📊 資料後台登入」。  
   - 輸入帳密後即可查看、下載或清除名單。

---

## 🧩 技術說明

- 前端技術：HTML + CSS（原生） + JavaScript  
- 資料儲存：Browser LocalStorage（可日後改接 Google Sheet / Firebase / Supabase）  
- 無需後端伺服器，可直接部署於：
  - GitHub Pages
  - Netlify
  - Vercel
  - Cloudflare Pages  

---

## 🧠 延伸應用建議

| 目的 | 作法 |
|------|------|
| 實際收單 | 改用 Google Apps Script 將表單寫入 Google Sheet |
| LINE 自動回覆 | 使用 LINE Messaging API 或 LINE LIFF 傳送感謝訊息 |
| 資料整合 | 串接 Notion / CRM 系統自動匯入名單 |
| 設計強化 | 套用 Noto Sans TC 字型或加入 Canva 設計背景 |

---

## 🏠 活動資訊

- **主辦單位**：起鈊厝  
- **協辦單位**：總管家住宅服務股份有限公司  
- **時間**：**12/19（五）19:00**  
- **地點**：**台中市北區臺灣大道二段340號九樓之2**  
- **主題**：危老重建｜免費60分鐘說明會  

---
