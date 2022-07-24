# GIT Commands

## Initial Setup
Step 1: Initialize your SpringBoot project <br />
- Go to start.spring.io
- Create a gradle project
- Create a repo with "spring web" dependency
- Download the file
- Unzip the file and copy it to your git folder in Windows Explorer

Step 2: Create the repo in git <br />
- Create an empty repo in GitHub (no readme)

Step 3: Initialize a local git repo
```
git init
git add .
git commit -m 'initial version'
git branch -M master
git remote add origin {your github url} 
git push origin master
```

## Subsequent Changes
Step 1: Switch to local master
```
git checkout master
git pull
```

Step 2: Create a new branch
```
git checkout -b {new-branch}
```

Step 3: Make changes

Step 4: Add changes and commit
```
git add .
git commit -m 'added logging'
git push origin {new-branch}
```

Step 5:  Go to GitHub and create a PR and merge to master

Then repeat from step 1 through step 4 for subsequent changes

