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
````
