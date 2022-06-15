# Delete A Stash

`git stash drop [stash@{<stash inedx>}]`

If there is no a specified stash, it will drop the top one.

**Example**
```git
$ git stash drop stash@{2}
```

**result**
```git
Dropped refs/stash@{0} (eae49c1e42f02757aa67b70efcddf497aa2a1015)
```