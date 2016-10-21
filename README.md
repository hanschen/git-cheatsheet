# Commands

## Create

TODO: initialize the git environment

    git init

TODO: "git clone" clones the file from the git repository to the directory that you are currently in (you may give it a new name in your directory, if you like).

    git clone


## Record changes

Display files changed since last commit.
Adding generated files to ```.gitignore``` stops them from appearing in this list.
It has separate sections for files that would be saved if you committed right now, for those files that have been changed since the last version it knows about, and for files it does not know about.

    git status

TODO: add explanation

    git add

TODO: add explanation

    git commit -v


## View history and changes

Show a breif description of changes to the repository.
My preference for a general overview is ```$ git log --graph --branches --remotes --pretty='format:%h %ad %an %d %s' --date=short```
To restrict the range of commits shown, use ```$ git log <commit id>..<commit id>```

    git log

TODO: add explanation

    git diff

TODO: add explanation

    git show

TODO: add explanation

    git checkout


## Undo things

TODO: add explanation

    git reset HEAD

TODO: add explanation

    git checkout --

TODO: add explanation

    git revert


## Branches

TODO: add explanation

    git checkout -b

TODO: add explanation

    git branch

TODO: add explanation

    git branch -d

TODO: add explanation

    git checkout

TODO: add explanation

    git merge


## Working with remotes

TODO: add explanation

    git remote -v

TODO: add explanation

    git remote add

TODO: add explanation

    git fetch

TODO: add explanation

    git pull

TODO: add explanation

    git push


# Vocabulary

* HEAD:
* branch:
* check out:
* clone:
* commit:
* fork:
* index:
* master:
* remote:
* repository:
* staging area:
* tag:
* upstream:
* version control system (vcs):
