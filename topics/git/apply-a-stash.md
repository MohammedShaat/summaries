# Apply A Stash

`git stash apply stash@{<stage index>}: `

If we didn't specify a stash name, top stash will be applied

**Example**
```git
$ git stash apply stash@{0}
```

**result**
```git
Already up to date!
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

```


## Pop A Stash

`git stash pop stash@{<stage index>}: `

This applies the stash/changes to the working directory and then delete the stash form the the stash stack

**Example**
```git
$ git stash pop stash@{2}
```

**result**
```git
Already up to date!
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Dropped stash@{2} (9b4e69fab6716b56de6856644e3c7d6b116c7010)

```