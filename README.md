# USEFUL-GIT-COMMANDS

### **Create a Repository**
**1. git init [project name]**<br />
To create a new repo, you'll use the git init command. git init is a one-time command you use during the initial setup of a new repo. Executing this command will create a new .git subdirectory in your current working directory. This will also create a new master branch.

**2. git clone [url]**<br />
Download a repository from a remote repository.

### **Observe your local repository**
**1. git status**<br />
Lists new or modified files that are not yet commited.

**2. git diff**<br />
Shows the changes to files that are not yet staged.

**3. git log**<br />
Shows full change history.

### **Working with branches**
**1. git branch**<br />
Lists all local branches.

**2. git branch -av**<br />
Lists all local branches, loal & remote.

**3. git checkout [my_branch]**<br />
Switch to a branch, my_branch, and update working directory.

**4. git branch [new_branch]**<br />
Create a new branch called new_branch.

**5. git branch -d [my_branch]**<br />
Delete my_branch.

**5. git checkout branch_b**<br />
**&nbsp; &nbsp; git merge branch_a**<br />
Merge branch_a into branch_b.

### **Make a change**
**1. git add .**<br />
Stage all changed files, ready for commit.

**2. git add [file]**<br />
Stages the file, ready for commit.

**3. git commit -m "commit message"**<br />
Commits all the staged files to local repository.

**4. git reset --hard**<br />
Revert everything to last commit.

### **Synchronize**
**1. git fetch**<br />
Get the latest changes from origin(no merge).

**2. git pull**<br />
Fetch the latest changes from origin and merge.

**3. git push**<br />
Push local changes to the origin.
