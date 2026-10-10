富股通 3.0｜iPhone PWA 安裝說明

一、部署（推薦 GitHub Pages）
1. 建立 GitHub 帳號並新增公開儲存庫，例如 fugutong。
2. 將這個資料夾內六個檔案全部上傳到儲存庫根目錄：index.html、app.js、manifest.webmanifest、sw.js、icon-192.png、icon-512.png。
3. 前往儲存庫 Settings → Pages → Build and deployment → Deploy from a branch；選 main 與 /(root)，按 Save。
4. 等候網站發布，GitHub Pages 會提供類似 https://帳號.github.io/fugutong/ 的 HTTPS 網址。
5. 用 iPhone Safari 開啟該網址，確認計算器正常運作。
6. 點 Safari 分享按鈕 → 加入主畫面 → 開啟為網頁 App（若顯示）→ 加入。
7. 從 iPhone 主畫面點「富股通」圖示即可開啟。第一次成功連線後，可嘗試離線使用。

二、重要提醒
- 不可只把 ZIP 直接加入 iPhone 主畫面；必須先部署成 HTTPS 網站。
- 操作紀錄及設定保存在該網站於本機的 localStorage，不會自動跨手機同步。請定期匯出 CSV。
- iOS 清除網站資料、移除網頁 App 或變更網域可能造成紀錄遺失。
- 手續費、證交稅估算僅供參考；特殊交易與優惠請用手動模式輸入實際金額。
- 程式不連接券商，也不會下單。
