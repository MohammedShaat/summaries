# List Tags

`git tag`

**Example**
```git
$ git tag
```

**result**
```git
v1.0
v1.1
v3
v4
```
\
And we can use a pattern by this command: `git tag -l "<pattern>"`.
Using `*` means anything aftet that.

**Example**
```git
$ git tag -l "v1*"
```

**result**
```git
v1.0
v1.1
```