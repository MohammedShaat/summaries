# List Branches

## List Only Local Branches

`git branch`

**Example**
```git
$ git branch
```

**result**
```git
  main
* update-branch
```


## List Local And Remote Branches

`git branch -a`

**Example**
```git
$ git branch -a
```

**result**
```git
  main
* update-branch
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  remotes/origin/update-branch
```