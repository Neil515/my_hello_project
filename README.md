# 📁 my_hello_project

這是一個用來模擬與學習 GitHub 專案管理、每日進度追蹤與 AI 工具整合的練習專案。  
目標是學會如何使用 GitHub、GitHub Desktop、Markdown、以及 `ai_progress.md` 來建立一個可以讓 AI 工具每天無縫接續的專案架構。

---

## 🧭 教學流程（已完成）

### ✅ 第 1 步：建立 GitHub 專案（雲端）
1. 登入 GitHub 並點選右上角 `＋` → `New repository`
2. 輸入 Repository 名稱：`my_hello_project`
3. 勾選：
   - `Add a README file`
   - `.gitignore` 選 None
4. 點選 `Create repository`

### ✅ 第 2 步：Clone 專案到本機
1. 開啟 GitHub Desktop → File → Clone repository
2. 選擇 `GitHub.com` 分頁 → 找到 `my_hello_project`
3. 選擇資料夾路徑：`C:\GitHubProjects\my_hello_project`（避免放在 OneDrive）

### ✅ 第 3 步：新增內容檔案
1. 在本機資料夾中手動新增兩個檔案：
   - `ai_progress.md`：記錄進度與預計下一步
   - `hello.txt`：簡單放一行文字：`Hello, AI! This is my first project.`
2. 開啟 GitHub Desktop → 勾選變更的兩個檔案
3. 填入 Commit 訊息：`新增 ai_progress.md 與 hello.txt 初始內容`

### ✅ 第 4 步：Commit + Push 回 GitHub
1. 點選 `Commit to main`
2. 然後點擊 `Push origin`
3. 確認 GitHub 網站已顯示這些更新

### ✅ 第 5 步：建立每日可接續進度的機制
1. 每天結束工作時，更新 `ai_progress.md` 三個區塊：
   - 最後更新日期
   - 今日完成項目
   - 下一步預計任務
2. 更新 `daily_checklist.md` 與（進階）`next_task_prompt.md`
3. 最後再次 Commit + Push，同步進度到 GitHub
4. 隔天開啟 AI 工具時，只需貼上：
