# 協作者修改指南

## 步驟 1: Fork 倉庫
1. **找到倉庫**：在瀏覽器中前往你想要協作的項目倉庫頁面。
2. **Fork 倉庫**：在倉庫頁面右上角，點擊“Fork”按鈕。這會在你的GitHub帳戶下創建該項目的副本。

## 步驟 2: 克隆 Fork 的倉庫
1. **打開GitHub桌面應用程序**：
   - 啟動GitHub桌面應用程序。如果沒有安裝，請先下載並安裝 [GitHub桌面應用程序](https://desktop.github.com/)。
2. **克隆倉庫**：
   - 在GitHub桌面應用程序中，點擊左上角的“File”菜單，然後選擇“Clone repository”。
   - 在彈出的窗口中，點擊“URL”標籤。
   - 在你的瀏覽器中，前往你Fork的倉庫頁面，點擊綠色的“Code”按鈕，複製HTTPS鏈接。
   - 將鏈接粘貼到“URL”字段中，然後點擊“Clone”。

## 步驟 3: 創建新分支
1. **創建新分支**：
   - 在GitHub桌面應用程序的頂部，點擊當前分支名稱（通常顯示為“Current Branch”）。
   - 在下拉菜單中，點擊“New Branch”。
   - 輸入新分支名稱（例如“my-new-feature”）並點擊“Create Branch”。

## 步驟 4: 編輯文件
1. **打開本地項目文件夾**：
   - 在GitHub桌面應用程序中，選擇你克隆的倉庫，然後選擇“Show in Finder”或“Show in Explorer”（根據你的操作系統）。這會打開你克隆的項目文件夾。
2. **選擇並編輯文件**：
   - 在文件管理器中，找到你需要編輯的文件。
   - 雙擊文件以打開它。你可以使用任何你喜歡的文本編輯器或IDE，比如：
     - Visual Studio Code
     - Sublime Text
     - Notepad++
     - Mac上的默認文本編輯器（TextEdit）
     - Windows上的默認文本編輯器（Notepad）
   - 在文本編輯器中，進行你需要的更改並保存文件。

## 步驟 5: 提交更改
1. **提交更改**：
   - 返回GitHub桌面應用程序，你會看到你的更改列在“Changes”標籤下。
   - 在“Summary”字段中輸入描述更改的消息（如“Added new feature”），然後點擊“Commit to <your-branch-name>”。

## 步驟 6: 推送更改到Fork的倉庫
1. **確保所有更改已經提交**：
   - 確保你在“Changes”標籤下方已經提交了所有更改。如果沒有提交，請參考步驟5提交更改。
2. **點擊“Push origin”按鈕**：
   - 在GitHub桌面應用程序的頂部，點擊“Push origin”按鈕。這個按鈕有時也會顯示為“Publish branch”或者“Push”。
   - 推送成功後，你會看到一個通知，提示你更改已成功推送到遠程倉庫。

## 步驟 7: 創建拉取請求（Pull Request）
1. **打開瀏覽器**：
   - 前往GitHub並登錄你的帳戶。
   - 導航到你Fork的倉庫頁面。例如，https://github.com/你的用戶名/項目名稱。
2. **點擊“Pull Requests”標籤**：
   - 在倉庫頁面的頂部菜單欄，點擊“Pull Requests”標籤。
3. **點擊“New Pull Request”按鈕**：
   - 點擊頁面右側的綠色“New Pull Request”按鈕。
4. **選擇比較分支**：
   - 在“Compare changes”頁面，選擇你Fork的倉庫和分支。確保“base repository”是原始倉庫，“base”是你要合併到的分支（例如“main”），而“head repository”是你Fork的倉庫，“compare”是你創建的新分支。
5. **查看並確認更改**：
   - GitHub會顯示你所做的更改。確認這些更改是你想要提交的。
6. **創建拉取請求**：
   - 點擊頁面右側的綠色“Create Pull Request”按鈕。
   - 添加拉取請求的標題和描述，說明你所做的更改以及更改的原因。
7. **提交拉取請求**：
   - 點擊“Create Pull Request”按鈕提交你的拉取請求。

倉庫的維護者會收到你的 Pull Request，並對其進行審核。如果一切順利，他們會將你的更改合併到主倉庫。
