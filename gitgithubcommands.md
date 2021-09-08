# Git & Github Commands List

## Cloning from GitHub:

1. Get SSH/HTTPS/GitHub CLI from code button in GH
2. cd into directory where we want to clone the repo to
3. ctrl + v to paste link [windows]
   cmd + v to paste link [mac]
4. Enter password, complete

SSH = `gh repo clone ASproson/gitdemo`
HTTPs = `git clone URL`

---

## Changing, committing, and pushing files:

1. `git add file.txt` *< adds to staging area*
1. `git add .` *< adds all files to staging area*
2. `git commit -m "Commit message"`
3. `git remote` *< tells us the repo on github we're pushing to*
3. `git remove -v` *< verbose of above*
4. `git push origin main` *< allows us to push to the repo*
       *where main is name of branch*

---

## Creating a repo locally then pushing to GitHub:

1. `cd` into place we want to create the repo
2. `git init` creates an empty repo locally
3. we do similar steps to the second section above via staging & committing
4. Go to GitHub and create the repo (making sure not to initialise) , collecting the SSH/HTTPS
5. `git remote add origin URL` *< connects to github repo*
6. `git remote` *< tells us the repo on github we're pushing to*
6. `git remove -v` *< verbose of above*
7. `git push origin main` *< allows us to push the repo [main =/= master]*

---

## Pulling changes from a repo

1. `git pull origin master` *< any changes made to main is pulled down locally*
