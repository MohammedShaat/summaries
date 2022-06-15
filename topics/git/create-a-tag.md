# Create A Tag

## Create A Lightweight Tag

`git tag <tag name> <optional commit id>`


**Example**
**1**
```git
$ git tag v1.0
```
If we didn't specify a commit, it will tags the HEAD's commit

**2**
```git

$ git tag v1.0 1834003
```

## Create An Annotated Tag

`git tag -a <tag name> -m "<message>" <optional commit id>`

**Annotated tag** is stored as a full object. Contains meta data like: tagger's name and email, , date, and message.


**Exampe**
**1**
```git
$ git tag -a v1.0 -m "This is a tag version 1.0"
```

**2**
```git
$ git tag -a v1.0 -m "This is a tag version 1.0" 1834003
```