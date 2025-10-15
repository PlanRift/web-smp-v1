# **👋 How to Contribute to This Project**

First off, thank you for considering contributing\! Open source projects like this one live and breathe because of awesome people like you who are willing to give their time and skills. We are excited to see your contributions.  
This guide will walk you through the entire process, step-by-step. Don't worry if you're new to this—we've all been there\!

## **Before You Start: Make Sure You Have Git**

To contribute code, you'll need a tool called Git to track changes and interact with GitHub. It's possible your computer already has it.

* **Windows:** Git does not come pre-installed. You can download it from the official website: [**git-scm.com/downloads**](https://git-scm.com/downloads). Run the installer and feel free to accept the default settings during installation.  
* **macOS & Linux:** Git is usually pre-installed. You can check by opening your terminal and typing git \--version. If you see a version number, you're all set\!

## **The Contribution Workflow 🚀**

We use the standard "Fork & Pull Request" model. Here's what that looks like:

1. **Fork** the project repository.  
2. **Clone** or **Download** your fork to your local machine.  
3. Create a new **branch** for your changes.  
4. Make your code changes.  
5. **Commit** and **push** your changes to your fork.  
6. Open a **Pull Request** to the main project.

Let's go through each step in detail.

### **Step 1: Fork the Repository**

A "fork" is your own personal copy of the project on GitHub. It's the place where you'll make your changes without affecting the main project.

* On the project's GitHub page, look for the **"Fork"** button in the top-right corner. Click it.  
* GitHub will ask you where to fork the repository. Choose your personal GitHub account.

### **Step 2: Get the Code on Your Computer**

Now, you need to get the code from your fork onto your computer. You can do this by "cloning" it (recommended for contributing) or downloading it.

#### **Option A: Clone Your Fork (Recommended)**

Cloning creates a connection to your fork on GitHub, which is necessary for pushing changes.

1. Go to the GitHub page for **your fork**.  
2. Click the green **\< \> Code** button.  
3. Copy the URL (it should look something like https://github.com/YOUR\_USERNAME/the-project-name.git).  
4. Open your terminal (or command prompt) and run this command:  
   git clone \[https://github.com/YOUR\_USERNAME/the-project-name.git\](https://github.com/YOUR\_USERNAME/the-project-name.git)

   *Be sure to replace YOUR\_USERNAME and the-project-name with the correct names\!*  
5. Now, navigate into the new project folder:  
   cd the-project-name

#### **Option B: Download the Code**

If you prefer not to use the command line for this step, you can download the code as a ZIP file.

1. On your fork's GitHub page, click the green **\< \> Code** button.  
2. Select **"Download ZIP"**.  
3. Unzip the file on your computer.

**Note:** Downloading is great for just exploring the code, but to contribute back, you will need to use Git. We recommend setting up Git and cloning the repository.

### **Step 3: Create a New Branch**

It's a best practice to create a new "branch" for every new feature or bug fix. This keeps your changes organized. Give your branch a descriptive name, like fix/login-button-bug.  
**Using the Terminal:**  
git checkout \-b your-branch-name

*(Example: git checkout \-b feature/add-dark-mode)*  
**VS Code Tip:** In VS Code's bottom-left corner, click the current branch name (it's probably main or master). A menu will open at the top. Select \+ Create new branch..., type your new branch name, and press Enter.

### **Step 4: Make Your Changes**

This is the fun part\! Open the project in your favorite code editor and make the edits you want to contribute.

### **Step 5: Commit Your Changes**

A "commit" is like a saved snapshot of your work.  
**Using the Terminal:**

1. Stage all your changed files:  
   git add .

2. Commit the changes with a descriptive message:  
   git commit \-m "feat: Add a dark mode toggle button"

**VS Code Tip:** Open the **Source Control** panel on the left sidebar.

1. Your changed files will be listed. Click the **\+** icon next to each file you want to include (stage).  
2. Type your commit message in the box at the top.  
3. Click the **Commit** button.

### **Step 6: Push Your Changes to Your Fork**

Your commit is currently only on your local machine. You need to "push" it up to your fork on GitHub.  
**Using the Terminal:**  
git push origin your-branch-name

**VS Code Tip:** After you commit, click the **"Publish Branch"** button that appears in the Source Control panel or in the bottom-left status bar. This will push your committed changes.

### **Step 7: Open a Pull Request (PR)**

This is the final step\! A "Pull Request" (PR) is how you propose your changes to the original project.

1. Go to the GitHub page for **your fork**.  
2. You should see a new banner that says **"your-branch-name had recent pushes"**. Click the green **"Compare & pull request"** button.  
3. This will take you to a new page.  
   * Give your pull request a clear **title**.  
   * In the **description box**, explain the changes you made and why. If you are fixing a specific issue, be sure to link it (e.g., "Fixes \#123").  
4. Click the **"Create pull request"** button.

### **You Did It\! 🎉**

Congratulations\! You've successfully created your first pull request. The project maintainers will now review your code, and they might ask for some changes. Once it's approved, they will merge your code into the main project.  
Thank you so much for your contribution\! ❤️