# git branches maintain

## using terminal commands

### how to create a branch 
git branch development

### how to checkout branch
git checkout development

### how to show all branches
git branch

### show the current branch details
git status

### remote repo(git) details give to local repo(your device)
#### (you can get updates to local repo)
git pull

### show remote repo updates higher than local repo
#### (only show ,you cannot get updates to local repo)
git fetch



## how to add a project in new git repository

git init
git add .
git commit -m "project init"
git branch -M main
git remote add (url)
git push -u origin main


## how to add a project in exists git repository

git add .
git commit -m "project init"
git push -u origin main






## using version control feature in vs code

### if you exsists in relevant branch

click the version control  in side bar.
type commit in blank space.
click the commit button and push  or
click the dropdown menu in commit button, and click the commit & push option.



### if you exsists in another branch

### you want to change branch , before adding new codings

click the version control menu in bottom bar, right side.
now popup the search bar and all branches.
if your branch already exists, you can click these branch.
if your branch does not exists, you can create new branch and checkout to these branch.
now you can code and after that commit and push to this branch using terminal or version control menu.


### you want to change branch , after added new codings

now you must go to the version control menu in side bar and click the three dots.
go to the stash option and click the stash(include untracked)
now popup blank stash space.
you must type the stash message and enter.
now you can change the branch in version control icon in bottom bar.
now you must click the three dots and go to the stash and click the apply stash...
now popup blank space in under the top bar. you must enter your stash messege and enter.
now you can commit and push.



