## Commands Basics for Git
![Error](https://www.solucionespm.com/wp-content/uploads/2018/11/GitHub.png)

Set the local Git repository to set its remote origin

```git remote add origin <repository URL>```

Pushing your commits to the online repository

```git push -u origin master```

Cloning an online repository

```git clone <repository URL>```

### Git config
This command sets the author name and email address respectively to be used with your commits.

```git config –global user.name '[name]'```

```git config –global user.email '[email address]'```

### Git init
This command is used to start a new repository.

```git init [repository name]```

### Git clone
This command is used to obtain a repository from an existing URL

```git clone [url]```

### Git add
This command adds a file to the staging area.

```git add [file]```
This command adds one or more to the staging area.

```git add *```

### Git commit
This command records or snapshots the file permanently in the version history.

```git commit -m '[ Type in the commit message]'```
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

```git commit -a```

### Git diff
This command shows the file differences which are not yet staged.

```git diff```
This command shows the differences between the files in the staging area and the latest version present.

```git diff –staged```
This command shows the differences between the two branches mentioned.

```git diff [first branch] [second branch]```

### Git reset
This command unstages the file, but it preserves the file contents.

```git reset [file]```
This command undoes all the commits after the specified commit and preserves the changes locally.

```git reset [commit]```
This command discards all history and goes back to the specified commit.

```git reset –hard [commit]```

### Git status
This command lists all the files that have to be committed.

```git status```

### Git rm
This command deletes the file from your working directory and stages the deletion.

```git rm [file]```

### Git log
This command is used to list the version history for the current branch.

```git log```
This command lists version history for a file, including the renaming of files also.

```git log -follow[file]```

### Git show
This command shows the metadata and content changes of the specified commit.

```git show [commit]```

### Git tag
This command is used to give tags to the specified commit.

```git tag [commitID]```

### Git branch
This command lists all the local branches in the current repository.

```git branch```
This command creates a new branch.

```git branch [branch name]```
This command deletes the feature branch.

```git branch -d [branch name]```

### Git checkout
This command is used to switch from one branch to another.

```git checkout [branch name]```
This command creates a new branch and also switches to it.

```git checkout -b [branch name]```

### Git merge
This command merges the specified branch’s history into the current branch.

```git merge [branch name]```

### Git remote
This command is used to connect your local repository to the remote server.

```git remote add [variable name] [Remote Server Link]```

### Git push
This command sends the committed changes of master branch to your remote repository.

```git push [variable name] master```
This command sends the branch commits to your remote repository.

```git push [variable name] [branch]```
This command pushes all branches to your remote repository.

```git push –all [variable name]``
This command deletes a branch on your remote repository.

```git push [variable name] :[branch name]```

### Git pull
This command fetches and merges changes on the remote server to your working directory.

```git pull [Repository Link]```

### Git stash
This command temporarily stores all the modified tracked files.

```git stash save```
This command restores the most recently stashed files.

```git stash pop```
This command lists all stashed changesets.

```git stash list```
This command discards the most recently stashed changeset.

```git stash drop```