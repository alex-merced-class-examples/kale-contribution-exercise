see what files are and arent in staging 
```
git status
```
Adding files to staging

```
git add filename.txt #Add a single file
git add -A #add all unstaged files throughout repo
git add . #add all files in current directory and sub directory

```


to commit 

```
git commit ## will open an editor to write a commit message (vim on mac)
git commit -m "commit message" #(standard way of commiting)

```

git remotes 
```
git remote add <name(usuall called origin)> <url (for the new repo)> <Branch Name> (named Main or master by default) ## add a remote

git remote rm <name> ##removes a remote

git remote -v # list all the current remotes

```

push and pull
```
git push <remote_name> <branch_name> ##sending the remote commits


```