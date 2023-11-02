## TERMINAL COMMANDS
-----
### CREATING A GIT REPOSITORY
```
git init 
```
Create git repo 

```
git add .
```
Add all files that are changed. Can also add specific files by typing in the name after add

```
git commit -m "Import release code"
```
If you don't have the -m then you can commit multiple line messages by taking out the -m and following string

```
git remote add origin <ADD SSH URL>
```
Get the SSH of the github you created on the web to add to the end. This sets which repo you want to push to. The name of this 
new repo is origin which we reference in the next command 

```
git branch -M main
```
Set current branch to name main or branch you want to push to

```
git commit --amend
```
Fix a commit message

```
git push -u origin main or git push --set-upstream origin main
```
Push to correct branch 

### SWITCHING BETWEEN REPOS IN TERMINAL
First thing you want to do is create the repository you would like to push to possibly through github website
To push to a specific repository on command line do this code, where the url is the 
```
git remote add origin <SOME-URL>/<SOME-REPOSITORY-NAME>.git
```

To check which repository you are pushing to: 
```
git remote -v 
```
-v stands for 'verbose' which returns the URLs of these remote origin 

If it is the wrong repository type 
```
git remote remove origin
```
And then add the origin with the desired SSH link

You can also just update the url 
```
git remote set-url <REMOTE-NAME> <NEW-URL>
```

[Cloudbees source](https://www.cloudbees.com/blog/remote-origin-already-exists-error)

### GIT BRANCHES

