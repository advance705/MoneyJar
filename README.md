# MoneyJar 0.0.11 beta

個人跨裝置記帳工具。

- [開啟帳本](https://advance705.github.io/MoneyJar/)
- [免登入合成示範](https://advance705.github.io/MoneyJar/#/demo)
- [舊版 v0.65.5 完整保留](https://github.com/advance705/MoneyJar/tree/archive/legacy-v0.65.5-20261105)，原提交 12080ff71dc2a8f0a5a06ed65e766cd1fb9baf0a。

帳務保存在各瀏覽器的 IndexedDB；網站程式更新不會清空帳本。初次切換來源，請下載新版 JSON 備份後在新來源匯入；舊版帳本格式尚不支援自動轉換。

Google 同步目前需要手動核對。跨裝置請使用同一 Google 帳號與同一 v2 資料夾，先同步再換裝置；不可當成背景自動同步已完成。每次使用後請下載 JSON 備份。

GitHub Pages 未提供自動行情，請在股票頁手動填價格和日期。透支利息仍依表單所列試算條件，需與銀行實際帳單核對。

本 repo 僅放已稽核的靜態程式與公開股票代號清單，沒有私人帳本、token、client secret 或本機資料。Phase 6 仍有待驗證項目，本版不是完整正式版。

## 回復舊版

從上述 archive 分支的 index.html 另存／複製回 main，使用新的正常提交恢復即可；保留 main 全部歷史，不使用 force push。不把 repo 設為 Archived，因為該操作會使整個 repo 唯讀。
