# 個人財務監控

記帳 + 資產監控的單頁網頁，資料存在 Google 試算表「個人財務監控」。

- `index.html`：整個應用程式（單一檔案）。在 GitHub Pages 開啟時用 Google 登入直接讀寫試算表；在 claude.ai 內開啟時改走連接器。
- 資料不在這個 repo。試算表維持「受限制」，只有授權的 Google 帳號能讀寫。
- OAuth 用戶端 ID 寫在 `index.html` 裡（非機密）。已授權的 JavaScript 來源必須和網站網址一致。

修改後直接編輯 `index.html` 並 push 到 main，Pages 會自動更新。
