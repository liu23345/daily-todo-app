# 日常清單｜待辦事項管理器

一個以 HTML、CSS、JavaScript 製作的響應式待辦事項 Web App，可直接部署到 GitHub Pages。

## 功能
- 新增任務、設定優先級與截止日期
- 標記完成 / 恢復未完成
- 全部、未完成、已完成篩選
- 編輯與刪除任務
- 顯示任務總數、待辦數、完成數與完成比例
- 清除已完成任務
- 使用瀏覽器 localStorage 保存資料
- 支援手機與桌面版面

## GitHub Pages 部署
1. 登入 GitHub，建立新的 **Public** repository，例如 `daily-todo-app`。
2. 將 `index.html` 上傳至 repository 根目錄（最外層）。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 中選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
6. 等待部署完成，網址通常會是 `https://你的GitHub帳號.github.io/daily-todo-app/`。
7. 開啟網址，實際測試新增、完成、篩選、編輯與刪除功能。

## 注意
- GitHub Pages 網址中的帳號與 repository 名稱需替換成自己的。
- 本 App 將任務存在目前瀏覽器的 localStorage，不會自動同步到其他裝置，也沒有雲端帳號系統。
