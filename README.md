# trainingGithub

Hey Guys,
I have a memento in order to modify files on github in 10 steps


## First step 
Clone your repository
```bash
    git clone  https://github.com/noam1610/trainingGithub
```


## Step two
Go to your repository in the terminal
```bash
    cd bla/bla/bla
```

## Step three
Synchronize your repository
```bash
    git sync
```


## Step four
Create new branch:
    1. If you will add something name it like this : feat-Iwillchangesomething
    2. If you will add something name it like this : fix-Iwillchangesomething

```bash
    git cob  feat-modification
```

## Step five
Write and change your file 

Sublime may be opened :
```bash
    subl .
```
## Step six
Commit your file in Git

```bash
    git cm "feat(app):un nom significatif"
```
## Step seven
Validate your work:

```bash
    git ready
```
Then you will see a VIM terminal:
To right in, you must press I in the keyboard.
Hence, you are in the insert mode : erase pick and replace it with r
Once it's done press esc
Then go to the down of the terminal and put :wq
Then you have a new window :

    Add
```bash
    Fixes #21
```
if 21 is the id of you issue


## Step eight
Now you are ready to push:

```bash
    git push
```

## Step nine
Go to github to cloture your pull/request

## Step ten

```bash
    git bdone
```


## Some interesting commands

To see all branches
```bash
    git b
```


To see the differences between master and you branch
```bash
    git d
```

To see non commited files
```bash
    git s
```

To see log messages
```bash
    git l
```

## Useful

Show the working tree status
```bash
    git status
```

Use git stash when you want to record the current state of the working directory and the index, but want to go back to a clean working directory. The command saves your local modifications away and reverts the working directory to match the HEAD commit.
```bash
    git stash
```

To replace last commit by a new one
```bash
git commit --amend
```

To commit in the futur:
```bash
git commit --date=1436876942
```

To undo something:
```
git reset
```

To create a new branch
```
git branch
```

To move to a branch
```
git checkout
```

Incorporates changes from a remote repository into the current branch
```
git pull
```

Show what revision and author last modified each line of a file
```
git blame 
```

Incorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch. This command is used by git pull to incorporate changes from another repository and can be used by hand to merge changes from one branch into another.
```
git merge
```

If you want to ungit a repo, just delete the git file with :
```
rm -rf .git
```

## Git alias

Our useful alias:

  **Create a new branch and go to it**
```
git cob
```

  **Add changes and commit it with "WIP" message**
```
git wip
```

  **Dealing with commit history**
```
git ready
```

**Dealing with commit history from master **
```
git ready-root
```

#### To change commit history

Use a **git ready**  
Use f to delete the commit message. If then you find a conflict, find the file concerned (git s), resolve it and save it (git add .)  
Then you can go on **git rebase --continue**

#### Problem of rebase 

If you have used a rebase, you have change the history so that you won't be able to push more because the trees don't match.
The solution is to force it:
```
git push -f
```

####To change the message of only one commit:

Use git ready but with the letter **r**

####Temporary notes
Typical commit message : "feat(app): First commit"



https://www.atlassian.com/git/tutorials/
http://git-scm.com/docs/git-pull
