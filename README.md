```
██╗  ██╗ ██████╗ ███╗   ███╗███████╗██╗    ██╗ ██████╗ ██████╗ ██╗  ██╗
██║  ██║██╔═══██╗████╗ ████║██╔════╝██║    ██║██╔═══██╗██╔══██╗██║ ██╔╝
███████║██║   ██║██╔████╔██║█████╗  ██║ █╗ ██║██║   ██║██████╔╝█████╔╝ 
██╔══██║██║   ██║██║╚██╔╝██║██╔══╝  ██║███╗██║██║   ██║██╔══██╗██╔═██╗ 
██║  ██║╚██████╔╝██║ ╚═╝ ██║███████╗╚███╔███╔╝╚██████╔╝██║  ██║██║  ██╗
╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝ ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```


---

# Guide: Fork, Homework, and Pull Request Workflow

This GitHub Repository contains homework for your python tasks. The tasks are located in [/tasks](/tasks/) folder. Completed homework lies under [/code](/code/) folder.

## Prerequisites:

1. **GitHub Account:**
   - Ensure that you have a GitHub account. If not, create one at [GitHub](https://github.com).

## Forking the Repository:

1. **Navigate to Your Repository:**
   - Go to your GitHub repository where the homework is hosted.

2. **Fork the Repository:**
   - Click on the "Fork" button at the top right of the repository page.
   - This creates a copy of the repository under your GitHub account.

## Cloning the Forked Repository:

1. **Copy Forked Repository URL:**
   - On your forked repository, click on the "Code" button and copy the HTTPS URL.

2. **Open Terminal (Linux/Mac) or Git Bash (Windows):**
   - Navigate to the directory where you want to clone your forked repository.

3. **Clone the Forked Repository:**
   - Run the following command:

     ```bash
     git clone https://github.com/malvere/PythonHomework.git
     ```

## Doing the Homework:

1. **Navigate to Cloned Forked Repository:**
   - Change into the cloned repository directory using the `cd` command:

     ```bash
     cd PythonHomework
     ```

2. **Create or Edit Homework Files:**
   - Create or edit the necessary homework files using your preferred text editor.

3. **Check Changes:**
   - Check the status of your changes with:

     ```bash
     git status
     ```

4. **Stage Changes:**
   - Stage your changes for commit:

     ```bash
     git add .
     ```

5. **Commit Changes:**
   - Commit your changes with a descriptive message:

     ```bash
     git commit -m "Add homework solution for Exercise 1"
     ```

6. **Push Changes to Forked Repository:**
   - Push your changes to your forked GitHub repository:

     ```bash
     git push origin main
     ```

   - If your default branch is named differently (e.g., `master`), replace `main` with your branch name.

## Creating a Pull Request:

1. **Navigate to Your Forked Repository on GitHub:**
   - Go to your forked repository on GitHub.

2. **Click on "Pull Request":**
   - Click on the "Pull Request" tab.

3. **Compare and Create Pull Request:**
   - GitHub will automatically detect the changes. Click on "Create Pull Request."

4. **Write Pull Request Description:**
   - Write a descriptive title and comment explaining the changes you made.

5. **Create Pull Request:**
   - Click on "Create Pull Request" to submit your homework.

## Conclusion:

You've successfully forked the repository, completed the homework, and created a pull request to submit it. This workflow allows for easy collaboration and contribution on GitHub.

---
