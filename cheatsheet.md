// to show your current status
git status

// a new repository is most easily created on github
- go to repositories and press the green new button
- clone it on your own computer with:
-$ git clone 'path'

// without github use in your command line
$ git init

// to update your git
$ git add *
$ git commit -a -m "comment"
$ git push

// To view your branches
$ git branch -avg

// create a new branch
$ git branch "new branch"

// switch to it, using
$ git checkout "branchname"

// to merge it into the curren HEAD
$ git merge "branchname"
  
// view history
$ git log

// to get stuff from github that someone else added
$ git pull

// quit vim
esc :wq

// save uncommitted changes since last commit in separate file and revert to last commit
$ git stash

// to totally reset to a previous commit. Don't really need this
$ git reset --hard
