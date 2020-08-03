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

### **Working with Remotes**
**1. git remote add <remote name> <url>**<br />
To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.
The git remote add command takes two arguments:
A remote name, for example, origin
A remote URL, for example, https://github.com/user/repo.git
Ex. git remote add origin https://github.com/user/repo.git

**2. git remote**<br />
It lists the shortnames of each remote handle you’ve specified. If you’ve cloned your repository, you should at least see origin — that is the default name Git gives to the server you cloned from.

**3. git remote -v**<br />
Verify new remote.

**4. git fetch <remote>**<br />
The command goes out to that remote project and pulls down all the data from that remote project that you don’t have yet.
Note: It only downloads the data to your local repository — it doesn’t automatically merge it with any of your work or modify what you’re currently working on. You have to merge it manually into your work when you’re ready.

**5. git clone**<br />
This command automatically sets up your local master branch to track the remote master branch (or whatever the default branch is called) on the server you cloned from.

**6. git push <remote> <branch>**<br />
When you have your project at a point that you want to share, you have to push it upstream.
Ex. git push origin master
  
**7. git remote rename**<br />
To change a remote’s shortname. For instance, if you want to rename pb to paul.
Ex. git remote rename pb paul

**8. git remote remove <remote>**<br />
If you want to remove a remote.
Ex. git remote remove sps

**9. git remote add origin [copied web address]**<br />
Copy the link in the input right beneath the title, it should look something like this: https://github.com/mindplace/test-repo.git This is the web address that your local folder will use to push its contents to the remote folder on Github.
Ex: git remote add origin https://github.com/mindplace/test-repo.git

### **Working with Tags**
