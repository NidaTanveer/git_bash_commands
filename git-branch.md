## branch  

-----if branch is present it will move/checkout to that branch or else it will create and will be checkout
```
git checkout -b main(bname)

```

-----creates branch but it will not be checkout
```
git branch main(bname) (inorder to checkout we need to use **git checkout branchn** command)
```

----- to checkout branch
```
git checkout main(bname) 
```

-----shows all the branches present
```
git branch 
```

after commit the changes won't go to remote only on pushing it will reflect the changes


# fork and clone

fork --- when we fork a repository we are saving a copy of repository only in our github account

clone --- to get the project in local we clone


## Merge
First the pr should be merged if not and branch is deleted it will close the pr without merge

initially checkout the branch in which u want the git1branch to merge example if u want to merge git1 into master 
1. checkout master 
2. use the below command
```
git merge branchname
```
### delete a branch

to delete a branch 
```git branch -d branchname

git push origin --delete branchname
```
