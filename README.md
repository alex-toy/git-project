# git with bash commands

### Manage Branches

- list branches
```
git branch 
```

- create branch
```
git branch new_branch
```

- change branch but remain on the current branch
```
git checkout new_branch
```

- change branch and move to it immediately
```
git checkout -b new_branch
```


### Basic Workflow

- stage file before commit
```
git add .
```

- unstage file before commit
```
git rm --cached file_to_unstage
```

- commit and push
```
git commit -m "commit message"
git push
```

- amend commit and push
```
git commit --amend -m "an updated commit message"
git push --force
```



 