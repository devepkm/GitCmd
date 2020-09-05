# Git Cmd
```cmd
git add .                         //add all files to git
git commit -m ""                  //commit with message


// new repo
git remote add origin [ssh]



// Branch

git branch -b [branchname]        //create new branch
git checkout [branchname]         // switch to branch
git branch -a                     //list all branch
git remote update origin --prune  //update branch from remote repository
git log --oneline [--graph]       //show log
git push origin -d [branchname]   //delete remote branch  


// ignore ds_store file
echo .DS_Store >> .gitignore
git add .gitignore
git commit -m '.DS_Store banished!'

```
