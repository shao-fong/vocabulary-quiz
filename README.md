# 單字網站 GitHub Pages 前端

這個資料夾只放公開前端檔案。不要放學生名冊、試算表匯出資料、GAS 原始碼或任何密鑰。

## 上線前設定

1. 在 `config.js` 設定 Cloudflare Worker 的公開 `/api` 網址。這個網址不是密鑰。
2. 確認 Worker 的允許來源 `SITE_ORIGIN` 與 GitHub Pages 網站來源完全相同。
3. 先在本機預覽頁面，再由 GitHub Pages 發布。

