# MoneyJar 0.0.13 beta

個人跨裝置記帳工具。

- [開啟帳本](https://advance705.github.io/MoneyJar/)
- [免登入合成示範](https://advance705.github.io/MoneyJar/#/demo)
- [舊版 v0.65.5 完整保留](https://github.com/advance705/MoneyJar/tree/archive/legacy-v0.65.5-20261105)，原提交 12080ff71dc2a8f0a5a06ed65e766cd1fb9baf0a。

帳務保存在各瀏覽器的 IndexedDB；網站程式更新不會清空帳本。初次切換來源，請下載新版 JSON 備份後在新來源匯入；舊版帳本格式尚不支援自動轉換。

Google 同步預設開啟背景排程：登入後更動約2秒自動上傳，每30秒及回到頁面時核對雲端；空白新裝置若只有一本既有帳本會自動備份及讀取。離線先存本機，恢復連線重試；兩邊都有修改會停止並保留雙方，不自動覆蓋。關閉前請等「已與 Drive 核對」；關閉後無法傳送，授權過期須重新登入。網站更新沿用同一帳本識別及Drive資料夾，格式變更會先備份再升級，未知格式停止而不清空。每次使用後請下載 JSON 備份。

GitHub Pages 未提供自動行情，請在股票頁手動填價格和日期。透支利息仍依表單所列試算條件，需與銀行實際帳單核對。

本 repo 僅放已稽核的靜態程式與公開股票代號清單，沒有私人帳本、token、client secret 或本機資料。Phase 6 仍有待驗證項目，本版不是完整正式版。

## 回復舊版

從上述 archive 分支的 index.html 另存／複製回 main，使用新的正常提交恢復即可；保留 main 全部歷史，不使用 force push。不把 repo 設為 Archived，因為該操作會使整個 repo 唯讀。
