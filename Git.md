## **Git commands and their uses**

### Configuration
- git config --global user.email "<email>"
- git config --global user.name "<name>"
- git config --list

### Repository Setup
- git init
- git clone <repository-url>

### Staging & Committing
- git status
- git add <file>
- git add .
- git commit -m "<commit message>"

### Branching
- git branch
- git branch <branch-name>
- git checkout <branch-name>
- git checkout -b <new-branch>
- git merge <branch-name>
- git branch -d <branch-name>

### Remote Repositories
- git remote -v
- git remote add origin <remote-url>
- git push -u origin <branch-name>
- git push
- git pull
- git fetch

### Viewing History & Logs
- git log
- git log --oneline
- git show <commit>

### Undoing Changes
- git reset
- git reset --hard
- git revert <commit>
- git checkout -- <file>

### Stashing
- git stash
- git stash apply
- git stash pop
- git stash list

### Tagging
- git tag <tag-name>
- git tag
- git push origin <tag-name>

### GitHub Specific (using GitHub CLI)
- gh auth login
- gh repo create <repo-name>
- gh issue list
- gh pr list

### Miscellaneous
- git diff
- git rm <file>
- git mv <old> <new>
- git clean -f

> Replace angle brackets <> with your values.
> For GitHub CLI commands, install GitHub CLI (`gh`) first.
