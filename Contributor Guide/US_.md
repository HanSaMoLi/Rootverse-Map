# Contributor Guide

## Step 1: Fork the Repository
1. **Find the repository**: Navigate to the project repository page you want to collaborate on in your browser.
2. **Fork the repository**: On the repository page, click the “Fork” button in the top right corner. This will create a copy of the project under your GitHub account.

## Step 2: Clone the Forked Repository
1. **Open GitHub Desktop**:
   - Launch the GitHub Desktop application. If you haven't installed it yet, download and install it from [GitHub Desktop](https://desktop.github.com/).
2. **Clone the repository**:
   - In GitHub Desktop, click on the “File” menu in the top left corner, then select “Clone repository”.
   - In the pop-up window, click the “URL” tab.
   - In your browser, go to the page of your forked repository, click the green “Code” button, and copy the HTTPS link.
   - Paste the link into the “URL” field and click “Clone”.

## Step 3: Create a New Branch
1. **Create a new branch**:
   - At the top of the GitHub Desktop application, click the current branch name (usually displayed as “Current Branch”).
   - In the drop-down menu, click “New Branch”.
   - Enter a name for your new branch (e.g., “my-new-feature”) and click “Create Branch”.

## Step 4: Edit Files
1. **Open the local project folder**:
   - In GitHub Desktop, select the repository you cloned, then select “Show in Finder” or “Show in Explorer” (depending on your operating system). This will open the local project folder.
2. **Select and edit files**:
   - In the file manager, find the file you need to edit.
   - Double-click the file to open it. You can use any text editor or IDE you prefer, such as:
     - Visual Studio Code
     - Sublime Text
     - Notepad++
     - Default text editor on Mac (TextEdit)
     - Default text editor on Windows (Notepad)
   - Make the necessary changes in the text editor and save the file.

## Step 5: Commit Changes
1. **Commit changes**:
   - Return to GitHub Desktop. You will see your changes listed under the “Changes” tab.
   - In the “Summary” field, enter a message describing your changes (e.g., “Added new feature”), then click “Commit to <your-branch-name>”.

## Step 6: Push Changes to the Forked Repository
1. **Ensure all changes are committed**:
   - Make sure all changes are committed under the “Changes” tab. If not, refer to Step 5 to commit the changes.
2. **Click the “Push origin” button**:
   - At the top of GitHub Desktop, click the “Push origin” button. This button may also appear as “Publish branch” or “Push”.
   - Once the push is successful, you will see a notification indicating that your changes have been successfully pushed to the remote repository.

## Step 7: Create a Pull Request
1. **Open your browser**:
   - Go to GitHub and log in to your account.
   - Navigate to the page of your forked repository. For example, https://github.com/your-username/repository-name.
2. **Click the “Pull Requests” tab**:
   - In the top menu bar of the repository page, click the “Pull Requests” tab.
3. **Click the “New Pull Request” button**:
   - Click the green “New Pull Request” button on the right side of the page.
4. **Select branches to compare**:
   - On the “Compare changes” page, select your forked repository and branch. Ensure that the “base repository” is the original repository, the “base” is the branch you want to merge into (e.g., “main”), and the “head repository” is your forked repository, and the “compare” is your newly created branch.
5. **Review and confirm changes**:
   - GitHub will display the changes you made. Confirm that these are the changes you want to submit.
6. **Create the Pull Request**:
   - Click the green “Create Pull Request” button on the right side of the page.
   - Add a title and description for the pull request, explaining the changes you made and why.
7. **Submit the Pull Request**:
   - Click the “Create Pull Request” button to submit your pull request.

## Step 8: Review and Merge
1. The repository maintainer will receive your Pull Request and review it.
2. If everything is in order, they will merge your changes into the main repository.
