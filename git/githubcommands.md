🔹 Basic Git Setup
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list

🔹 Repository Commands
git init                 # Initialize a repo
git clone <repo-url>     # Clone a repository

🔹 Working Directory Commands
git status               # Check file status
git add <file>           # Add file to staging
git add .                # Add all files
git restore <file>       # Discard changes
git rm <file>            # Delete file

🔹 Commit Commands
git commit -m "message"  # Commit changes
git commit -a -m "msg"   # Add + commit tracked files
git log                  # View commit history
git log --oneline
git show <commit-id>

🔹 Branching Commands
git branch               # List branches
git branch <name>        # Create branch
git checkout <branch>    # Switch branch
git checkout -b <name>   # Create & switch
git switch <branch>      # New way to switch
git merge <branch>       # Merge branch
git branch -d <branch>   # Delete branch

🔹 Remote Repository Commands
git remote -v
git remote add origin <url>
git push origin <branch>
git push -u origin main
git pull
git fetch

🔹 Undo / Reset Commands
git reset <file>                 # Unstage file
git reset --soft HEAD~1          # Undo commit (keep changes)
git reset --hard HEAD~1          # Undo commit (delete changes)
git revert <commit-id>           # Safe undo

🔹 Stash Commands
git stash
git stash list
git stash apply
git stash pop
git stash drop

🔹 Tag Commands
git tag
git tag v1.0
git show v1.0

🔹 Difference & Inspection
git diff
git diff --staged
git blame <file>

🔹 Helpful Shortcuts
git clean -f
git reflog
git cherry-pick <commit-id>

🔥 Most Important for Exams & Interviews