# 协作者修改指南

## 步骤 1: Fork 仓库
1. **找到仓库**：在浏览器中前往你想要协作的项目仓库页面。
2. **Fork 仓库**：在仓库页面右上角，点击“Fork”按钮。这会在你的GitHub账户下创建该项目的副本。

## 步骤 2: 克隆 Fork 的仓库
1. **打开GitHub桌面应用程序**：
   - 启动GitHub桌面应用程序。如果没有安装，请先下载并安装 [GitHub桌面应用程序](https://desktop.github.com/)。
2. **克隆仓库**：
   - 在GitHub桌面应用程序中，点击左上角的“File”菜单，然后选择“Clone repository”。
   - 在弹出的窗口中，点击“URL”标签。
   - 在你的浏览器中，前往你Fork的仓库页面，点击绿色的“Code”按钮，复制HTTPS链接。
   - 将链接粘贴到“URL”字段中，然后点击“Clone”。

## 步骤 3: 创建新分支
1. **创建新分支**：
   - 在GitHub桌面应用程序的顶部，点击当前分支名称（通常显示为“Current Branch”）。
   - 在下拉菜单中，点击“New Branch”。
   - 输入新分支名称（例如“my-new-feature”）并点击“Create Branch”。

## 步骤 4: 编辑文件
1. **打开本地项目文件夹**：
   - 在GitHub桌面应用程序中，选择你克隆的仓库，然后选择“Show in Finder”或“Show in Explorer”（根据你的操作系统）。这会打开你克隆的项目文件夹。
2. **选择并编辑文件**：
   - 在文件管理器中，找到你需要编辑的文件。
   - 双击文件以打开它。你可以使用任何你喜欢的文本编辑器或IDE，比如：
     - Visual Studio Code
     - Sublime Text
     - Notepad++
     - Mac上的默认文本编辑器（TextEdit）
     - Windows上的默认文本编辑器（Notepad）
   - 在文本编辑器中，进行你需要的更改并保存文件。

## 步骤 5: 提交更改
1. **提交更改**：
   - 返回GitHub桌面应用程序，你会看到你的更改列在“Changes”标签下。
   - 在“Summary”字段中输入描述更改的消息（如“Added new feature”），然后点击“Commit to <your-branch-name>”。

## 步骤 6: 推送更改到Fork的仓库
1. **确保所有更改已经提交**：
   - 确保你在“Changes”标签下方已经提交了所有更改。如果没有提交，请参考步骤5提交更改。
2. **点击“Push origin”按钮**：
   - 在GitHub桌面应用程序的顶部，点击“Push origin”按钮。这个按钮有时也会显示为“Publish branch”或者“Push”。
   - 推送成功后，你会看到一个通知，提示你更改已成功推送到远程仓库。

## 步骤 7: 创建拉取请求（Pull Request）
1. **打开浏览器**：
   - 前往GitHub并登录你的账户。
   - 导航到你Fork的仓库页面。例如，https://github.com/你的用户名/项目名称。
2. **点击“Pull Requests”标签**：
   - 在仓库页面的顶部菜单栏，点击“Pull Requests”标签。
3. **点击“New Pull Request”按钮**：
   - 点击页面右侧的绿色“New Pull Request”按钮。
4. **选择比较分支**：
   - 在“Compare changes”页面，选择你Fork的仓库和分支。确保“base repository”是原始仓库，“base”是你要合并到的分支（例如“main”），而“head repository”是你Fork的仓库，“compare”是你创建的新分支。
5. **查看并确认更改**：
   - GitHub会显示你所做的更改。确认这些更改是你想要提交的。
6. **创建拉取请求**：
   - 点击页面右侧的绿色“Create Pull Request”按钮。
   - 添加拉取请求的标题和描述，说明你所做的更改以及更改的原因。
7. **提交拉取请求**：
   - 点击“Create Pull Request”按钮提交你的拉取请求。

仓库的维护者会收到你的 Pull Request，并对其进行审核。如果一切顺利，他们会将你的更改合并到主仓库。
