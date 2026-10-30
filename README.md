# AiKESO@Home 院外頁面（GitHub Pages）

- `pt.html`：病人端。病人連結：`pt.html?bed=V01`（床號已帶入，病人只需輸入密碼）。
- `doc.html`：醫師端（員工編號登入）。
- `rn.html`：到府派工（護理端，員工編號登入）。
- 三頁都透過 Google Apps Script 後端 API 與院內戰情室共用同一份資料，不需要 Claude 帳號；時間為真實時間。
- 啟用方式：Settings → Pages → Source: Deploy from a branch → main / (root) → Save。
- 網址：`https://glennxxx2002-cloud.github.io/aikeso-home/pt.html?bed=V01`、`…/doc.html`、`…/rn.html`

所有病人皆為虛構示範資料。
