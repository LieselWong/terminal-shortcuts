## TERMINAL COMMANDS

### ~ CUSTOMIZING TERMINAL ~
 
https://www.youtube.com/watch?v=C92eaq_bZR8 

https://www.notion.so/Customizing-Your-Bash-Prompt-ef312daad923421c859bda
89a5dd1792
^above is a link that got cut off

https://www.youtube.com/watch?v=ilRVbYvKPEM

------
common special characters in terminal: 
- \d - current date
- \h - host name
- \u - username of current user 
- \t - current time in military HH:MM:SS
- \@ - current time in 12 hour HH:MM am/pm
- \w - path to current working directory 

ex: PS1="I am \u " in the home directory changes terminal prompt to I am 
\u ***IDK WHY THE SPECIAL CHARACTER ISN'T WORKING

common terminal customization: PS1="\h:\u" 

***ISSUE: special characters weren't working in terminal***

-----
### CREATING A GIT REPOSITORY
```
echo "# cs3110-a4" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <REPO'S SSH URL>
git push -u origin main
```

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
First thing is to create a branch from your git repository and pull from main 

We then want to be able to access this remote branch from our terminal. Type 
```
git branch -r
```

Then to get the branch you just created
```
git fetch 
```

And then finally switch to the branch you want using 
```
git switch <name-of-branch>
```



