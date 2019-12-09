# Using GitHub
How to navigate the project repo
## How to deal with github
- Read: [Introduction to Git and the Command line](https://sklise.com/2012/09/22/introduction-to-git/).
- Read: [Git Workflow for Beginners](https://sklise.com/2012/10/07/git-workflow-beginner/).

## How to update the repo from the command line

### For the first time: 

1) Go to terminal/command line
2) Navigate to the project folder (using cd) 
3) Clone the repo to create a local copy on your computer by clicking "clone" under the repo name to copy the clone url 
4) Go back to terminal 
5) Type in this command and paste the url you copied 
```
git clone git@github.com:username/reponame.git
```
6) Press enter. That should clone the repo.
7) Navigate to the new folder that is now under your project folder 
8) Execute the commands below 

### After Cloning:

1) Go to terminal/command line
2) Navigate to the project folder (using cd) 
3) Execute the following commands

```
git add .
git commit -m "your commit message"
git push origin master
```
To check what's going on, use

```
git status
```
### How to pull from the remote repo using the command line
```
git pull origin master
```
### Alternatively, download github desktop! Could make your life easier? I personally don't like it:)
Download here: https://desktop.github.com/
