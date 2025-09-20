# Learning Git

A hands-on tutorial for learning Git version control basics.

## Tutorial Videos

📹 [Git Tutorial Video](https://www.youtube.com/watch?v=85Hhpn1-i0E) - Quick introduction to Git basics

📺 [Complete Git and GitHub Tutorial](https://www.youtube.com/watch?v=S7XpTAnSDL4) - Comprehensive guide covering Git and GitHub

## Git Commands Used in This Session

This tutorial covers the essential Git commands I've learned and practiced:

### 1. Installing Git
```bash
brew install git
```
Installs Git on macOS using Homebrew.

### 2. Checking Git Version
```bash
git --version
```
Verifies that Git is installed and shows the current version.

### 3. Global Configuration
```bash
git config --global user.name "freebeerstudio"
git config --global user.email "wayne@freebeer.ai"
```
Sets up your identity for Git commits. This information will be attached to all your commits.

### 4. Viewing Configuration
```bash
git config --list
```
Displays all your current Git configuration settings.

### 5. Cloning a Repository
```bash
git clone git@github.com:freebeerstudio/learning_git.git
```
Downloads a copy of a remote repository to your local machine.

### 6. Viewing Commit History
```bash
git --no-pager log --oneline -10
```
Shows the last 10 commits in a condensed format. The `--no-pager` flag prevents pagination.

## Key Concepts Learned

- **Repository (Repo)**: A directory that contains your project files and Git's tracking information
- **Clone**: Creating a local copy of a remote repository
- **Commit**: A snapshot of your project at a specific point in time
- **Configuration**: Setting up Git with your personal information

## Next Steps

Now that you have the basics down, you can explore:
- Making changes and committing them
- Working with branches
- Pushing changes back to the remote repository
- Collaborating with others

## Resources

- [Git Official Documentation](https://git-scm.com/doc)
- [Git Tutorial Video](https://www.youtube.com/watch?v=85Hhpn1-i0E) - Quick introduction
- [Complete Git and GitHub Tutorial](https://www.youtube.com/watch?v=S7XpTAnSDL4) - Comprehensive guide
- [GitHub Git Handbook](https://guides.github.com/introduction/git-handbook/)
