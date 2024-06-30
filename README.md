# GIT

### Git Tutorial for Beginners

#### 1. What is Git?

- Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
- It tracks changes to files, allowing multiple people to work on them simultaneously, coordinating their work seamlessly.

#### 2. Installing Git

- **Linux**: Install via package manager (`apt`, `yum`, etc.).
  ```bash
  sudo apt-get install git  # Debian/Ubuntu
  sudo yum install git      # CentOS/Fedora
  ```
- **Mac**: Install Git using Homebrew or download from the Git website.
  ```bash
  brew install git         # Homebrew
  ```
- **Windows**: Download and install from [Git for Windows](https://gitforwindows.org/).

#### 3. Configuring Git

- Set your username and email address:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

#### 4. Creating a Git Repository

- Initialize a new Git repository:
  ```bash
  git init
  ```

#### 5. Basic Git Workflow

- **Checking Status**:
  ```bash
  git status
  ```

- **Adding Files**:
  ```bash
  git add <filename>     # Stage specific file
  git add .              # Stage all files
  ```

- **Committing Changes**:
  ```bash
  git commit -m "Commit message"
  ```

#### 6. Branching and Merging

- **Creating a Branch**:
  ```bash
  git branch <branch-name>
  git checkout <branch-name>   # Switch to the new branch
  ```

- **Merging Branches**:
  ```bash
  git checkout main           # Switch to main branch (or target branch)
  git merge <branch-name>     # Merge changes from <branch-name> into main
  ```

#### 7. Remote Repositories (GitHub)

- **Linking to a Remote Repository**:
  ```bash
  git remote add origin <remote-url>   # Add a remote repository
  ```

- **Pushing Changes**:
  ```bash
  git push -u origin main     # Push local changes to the remote repository
  ```

- **Pulling Changes**:
  ```bash
  git pull origin main        # Pull latest changes from remote repository
  ```

#### 8. Resolving Conflicts

- **Conflict Resolution**:
  - Edit conflicted files to resolve conflicts.
  - Add resolved files using `git add` and commit changes.

#### 9. Git History and Log

- **Viewing Commit History**:
  ```bash
  git log                # View commit history
  git log --oneline      # Compact view of commit history
  ```

#### 10. Additional Git Commands

- **Undoing Changes**:
  ```bash
  git reset HEAD <filename>   # Unstage changes
  git checkout -- <filename>  # Discard changes in working directory
  ```

- **Git Help**:
  ```bash
  git --help             # Git command help
  ```

#### 11. Git Resources

- Official Git Documentation: [Git SCM](https://git-scm.com/doc)
- GitHub Guides: [GitHub Docs](https://docs.github.com/en/github)
- Interactive Learning: [Git - Learn](https://learngitbranching.js.org/)
