# List All Files And Hidden Files

`ls -a`

**Example**
```
$ ls -a
```

**result**
```
./  ../  .git/  .gitignore  LICENSE  readme.md  topics/  trash/
```

## List one File Per Line

`ls -a1`

**Example**
```
$ ls -a1
```

**result**
```
./
../
.git/
.gitignore
LICENSE
readme.md
topics/
trash/
```

## List With Details

`ls -al`

**Example**
```
$ ls -al
```

**result**
```
total 28
drwxr-xr-x 1 HP 197121     0 Jun 14 10:25 ./
drwxr-xr-x 1 HP 197121     0 Jun 11 18:07 ../
drwxr-xr-x 1 HP 197121     0 Jun 14 10:29 .git/
-rw-r--r-- 1 HP 197121  1610 Jun 11 18:06 .gitignore
-rw-r--r-- 1 HP 197121 11357 Jun 11 18:06 LICENSE
-rw-r--r-- 1 HP 197121  3515 Jun 14 11:18 readme.md
drwxr-xr-x 1 HP 197121     0 Jun 14 10:33 topics/
drwxr-xr-x 1 HP 197121     0 Jun 14 10:25 trash/
```
