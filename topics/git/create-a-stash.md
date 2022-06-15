# Create A Stash

**Stash:** Temporarily stashes/hides changes which in the working directory and staging area, to reapply them later.

Let's say that you are doing some changes on your project and in the mid of the way you decided to do something else but at the same time you don't want to lose what you are doing, here comes the importance of *stash*

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