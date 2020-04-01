Linux Commands
============
| Command | Description |
| ------- | ----------- |
| `pwd` | Displays the present working directory |
| `ls -la` | List all the content of a directory including the hidden files and directories. |
| `mkdir -p` | Create a new directory, provided it doesn't exists. |
| `touch 'filename'` | Create a new file |
| `rm -r -f filename`	| rm files (folders) |
| `find ~ -type d -iname "Documents"` |  find folders |

Git Commands
============

### Setting up Repository

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone link` | Create a local copy of a remote repository |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git config --global user.email "you@example.com"` | Define your git email|
| `git config --global user.name "Your Name"` | Define your git username|
| `git commit -m "[commit message]"` | Commit changes |
| `git reset --soft HEAD~1` | undo the last commit and perform additional modifications. |
| `git reset --hard HEAD~1` | undo the last commit and discard all changes in the working directory and index |
| `git rm -r [file-name.txt]` | Remove a file (-r for removing folder) |

### Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin "link.git"` | Add a remote repository |
| `git remote set-url origin "link.git"` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |
