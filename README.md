# SHORTCUT

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

