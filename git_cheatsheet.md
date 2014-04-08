git init initializes a git repository
git add <filename> adds a file or changes in a file to a repository
git add . adds everything in current directory (files and changes) to a repository
git commit -m <meassage> saves changes you've made to the repository
git reset <Log Number> resets git repo to specific commit
git reset --hard <Log Number> reset git repo, and current directory to specific commit

git commit --amend Adds changes to previous commit

git commit --amend -m "New message" changes your previous commit message
git remote add <remote_name> <url> connects repo to a remote url (usually github)
git remote rm <remote_name> removes a previously added remote
git remote -v lists all of your remotes

git push <remote_name> <branch> pushes changes to a remote git repo (usually github)

git fetch <remote_name> <branch> fetches change from a remote, but does not merge into local repo
git pull <remote_name> <branch> pulls and merges changes from a remote git repo (usually github)

git clone <url> copy's a repo from github
git branch lists different branches
git branch <new_branch_name> creates a new branch
git checkout <branch_name> moves you to the branch specified
git checkout -b <new_branch_name> creates a new branch, and moves you to new branch

git merge <branch_name> merges the specified branch into the working branch
git help lists possible git commands
git status shows changes that have not been committed
git log shows commit history
git diff show changes between commits, commit and working tree, etc

git config --global user.name "John Doe" sets a name that will be attached to commits

git config --global user.email johndoe@example.com sets an email that will be attached to commits
