### Task: Create a Repository, Make Changes, and Push to GitHub

1. **Install Git:**
   - If Git is not installed, download and install it from [here](https://git-scm.com/downloads).

2. **Set Up Git:**
   - Open the terminal (or Git Bash on Windows) and configure Git with your name and email:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

3. **Create a Local Repository:**
   - Create a new directory for your project and navigate into it:
     ```bash
     mkdir my_first_git_repo
     cd my_first_git_repo
     ```
   - Initialize a new Git repository:
     ```bash
     git init
     ```

4. **Create a File and Make Your First Commit:**
   - Create a new file called `README.md` and open it in a text editor. Add some text (e.g., "This is my first Git repository.").
   - Save the file and go back to the terminal.
   - Check the status of your repository:
     ```bash
     git status
     ```
   - Add the file to the staging area:
     ```bash
     git add README.md
     ```
   - Commit the file to the repository:
     ```bash
     git commit -m "Add README.md file"
     ```

5. **Create a Repository on GitHub:**
   - Go to [GitHub](https://github.com) and log in or create an account.
   - Create a new repository called `my_first_git_repo` (leave it empty, without a README, .gitignore, or license).

6. **Push Your Local Repository to GitHub:**
   - In the terminal, add the GitHub repository as a remote:
     ```bash
     git remote add origin https://github.com/yourusername/my_first_git_repo.git
     ```
   - Push your local commits to the GitHub repository:
     ```bash
     git push -u origin master
     ```

### Summary of Commands:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
mkdir my_first_git_repo
cd my_first_git_repo
git init
echo "This is my first Git repository." > README.md
git status
git add README.md
git commit -m "Add README.md file"
git remote add origin https://github.com/yourusername/my_first_git_repo.git
git push -u origin master
```

This task will help your friend get started with Git by setting up a repository, making an initial commit, and pushing the changes to GitHub.