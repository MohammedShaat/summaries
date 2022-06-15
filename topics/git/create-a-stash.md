# Create A Stash

`git stash`

**Example**
```git
$ git stash
```

**result**
```git
The file will have its original line endings in your working directory
Saved working directory and index state WIP on master: e342f2d Add news.txt
```


## Create A Stash With Name

`git stash save <stash name>`

**Example**
```git
$ git stash "Modified readme.md"
```

**result**
```git
Saved working directory and index state On master: Modified readme.md
```