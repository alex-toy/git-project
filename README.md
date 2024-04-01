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


### Git rebase

- rebase
```
git rebase base_branch
```

