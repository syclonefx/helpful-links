# Learning Git
### Learn Git with Bitbucket Cloud
[https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)   
### Bitbucket .gitignore tutorials
[https://www.atlassian.com/git/tutorials/gitignore](https://www.atlassian.com/git/tutorials/gitignore)   
### Clone a Git
```
git clone git@github.com:syclonefx/pixel-city.git
```
## Add, commit, pull, push
### Add all files to repo 
```
git add -a
```
### Commit 
```
git commit -m “<INSERT MESSAGE HERE>”
```
Status
```
git status
```
Pull
```
git pull origin <BRANCH NAME>
```
Push
```
git push origin <BRANCH NAME>
```
Check out a brach: 
```
git checkout <BRANCH NAME>
```
Create a new branch: 
```
git checkout -b <BRANCH NAME>
```
View Branches
```
git branch
```
[https://stackoverflow.com/questions/14168677/merge-development-branch-with-master](https://stackoverflow.com/questions/14168677/merge-development-branch-with-master)   
### Merge
```
git merge
git merge master
git checkout master
git merge <PREVIOUS BRANCH NAME> 
```
[https://makandracards.com/makandra/621-git-delete-a-branch-local-or-remote](https://makandracards.com/makandra/621-git-delete-a-branch-local-or-remote)   
### Delete local branch
```
git branch -d <BRANCH NAME>
```
### Delete remote branch
```
git push origin —delete <BRANCH NAME>
```
[https://stackoverflow.com/questions/11302639/delete-forked-repo-from-github](https://stackoverflow.com/questions/11302639/delete-forked-repo-from-github)   
[https://help.github.com/en/articles/adding-a-remote](https://help.github.com/en/articles/adding-a-remote)   
### Add a remote repo to a local repo
```
git remote add origin <URL of remote>
git fetch origin
git pull origin master
```

### Verify remote 
```
git remote -v
```