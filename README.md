# Cloning an Existing Repository:
```git clone repository ‘HTTPS or SSH’ dir```—(new directory name *optional)

# Git Status:
```git status``` — Checking the Status of Your Files

```git status  -s```  — Checking the Status of Your Files in sort way **

```git add (file_name)``` — Track this file

```git restore --staged (file_name)``` — Untrack this file from staged list

```git log —n ``` —show last n commit history

```git clean -df``` — will remove all the untracked directories and untracked files.

# Git Amend:
``` git add . ```

``` git commit --amend -m 'messege' ``` — modify last commit

# Git Branch:
```Clone the repository```

```Git branch (branch_name)``` — create new branch

```Git checkout (branch_name)``` — switch one branch to another

```git push –set-upstream origin (branch_name)``` — push branch to remote

```git branch -m <old_name> <new_name>``` to rename branches. Use -D for force deletion, -r to list the remote branches only, & -a to see all branches.

# Pull from remote branch:
```git remote add origin (branch_ssh)```

```git pull origin (branch_name)```

```git push origin (local branch):(remote_branch)```

