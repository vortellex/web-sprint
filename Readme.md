# Beginner's Guide: Forking a Repository and Raising a Pull Request (PR)

## 🚀 What is Forking and Pull Request?
- **Forking**: Creating a copy of someone else's repository under your GitHub account.
- **Pull Request (PR)**: Requesting the original repository owner to merge your changes.

## 📌 Steps to Fork and Raise a Pull Request

### Step 1: Fork the Repository
1. **Go to the GitHub repository** you want to contribute to.
2. Click the **Fork** button (top-right corner) to create a copy in your GitHub account.

### Step 2: Clone the Forked Repository
1. Navigate to your forked repository (`https://github.com/your-username/repository-name`).
2. Click the **Code** button and copy the URL (HTTPS or SSH).
3. Open a terminal (or Git Bash) and run:
   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```
4. Navigate to the project folder:
   ```sh
   cd repository-name
   ```

### Step 3: Create a New Branch
1. Create and switch to a new branch:
   ```sh
   git checkout -b feature-branch
   ```
2. Make your changes in the code.

### Step 4: Commit and Push Changes
1. Stage the changes:
   ```sh
   git add .
   ```
2. Commit the changes:
   ```sh
   git commit -m "Added new feature/fixed issue"
   ```
3. Push the changes to your forked repository:
   ```sh
   git push origin feature-branch
   ```

### Step 5: Create a Pull Request (PR)
1. Go to your forked repository on GitHub.
2. Click the **Compare & pull request** button.
3. Add a **title and description** of your changes.
4. Click **Create Pull Request**.
5. Wait for maintainers to review and merge your changes! 🎉

## 🎯 Conclusion
Congratulations! You now know how to **fork a repository, make changes, and create a PR**. Happy coding! 🚀
