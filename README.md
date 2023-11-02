# SHORTCUTS

## MACOS KEYBOARD SHORTCUTS
-----
```
command / 
```
Adds comments around the line 

```
shift ( 
```
Adds parenthesis around a line

## TERMINAL COMMANDS
-----
### CREATING A GIT REPOSITORY
```
git init 
```
Create git repo 

```
git remote add origin <ADD SSH URL>
```
Get the SSH of the github you created on the web to add to the end. This sets which repo you want to push to. The name of this 
new repo is origin which we reference in the next command 

```
git push --set-upstream origin <INSERT-NAME-OF-BRANCH-YOU-WANT-TO-PUSH-TO>
```
Push to correct branch 

### GENERAL COMMANDS
```
unzip (name of zip file)
```
unzips file 

```
ls -a
```
Shows all files in the github code including .gitignore or other formatting files ssh clone link

```
git commit --amend
```
Fix a commit message

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

