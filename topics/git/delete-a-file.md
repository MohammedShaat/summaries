# Delete A File

Using **git:** `git rm <old file name> <new file name>`

**Example**
```
$ git rm readme.md
```

\
 Sometimes fails to delete the file because it's staged, so you can use `-f`.
 **Example**:
 ```
 $ git rm -f readme.md
 ```

\
Or using **bash:** `rm <old file name> <new file name>`