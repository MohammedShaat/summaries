# List All Files Except Hidden Files

`ls`

**Example**
```
$ ls
```

**result**
```
LICENSE  readme.md  topics/  trash/
```

## List one File Per Line

`ls -1`

**Example**
```
$ ls -1
```

**result**
```
LICENSE
readme.md
topics/
trash/
```

## List With Details

`ls -l`

**Example**
```
$ ls -l
```

**result**
```
total 16
-rw-r--r-- 1 HP 197121 11357 Jun 11 18:06 LICENSE
-rw-r--r-- 1 HP 197121  3306 Jun 14 11:09 readme.md
drwxr-xr-x 1 HP 197121     0 Jun 14 10:33 topics/
drwxr-xr-x 1 HP 197121     0 Jun 14 10:25 trash/
```