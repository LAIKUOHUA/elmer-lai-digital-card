# Elmer LAI Digital Card

這是一個零依賴的靜態網站，直接上傳 `outputs` 資料夾即可部署。

## 本機預覽

用瀏覽器開啟 `index.html` 即可預覽；若要測試 QR Code，請使用 `http://localhost` 或部署後的網址。

## 部署

- Vercel：將此資料夾拖到 Vercel，或將資料夾內容放入 Git repository 後 Import。
- GitHub Pages / Netlify：上傳 `index.html`、`style.css`、`script.js` 三個檔案。

## 替換頭像與連結

目前頭像是 `EL` 文字佔位區。將 `index.html` 的 `.avatar` 內容替換成 `<img src="photo.jpg" alt="賴國華">`，並把照片放在同一資料夾即可。網站／社群連結則在 `index.html` 的 `data-placeholder` 那一列更新 `href` 與顯示文字。

QR Code 目前使用 QRServer 公開 API 產生；若需要完全離線版本，可改用本地 QR Code 套件或固定圖片。
