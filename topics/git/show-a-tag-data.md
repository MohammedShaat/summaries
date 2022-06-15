# Show A Tag's Data

`git show <tag name>`

It shows the **tag**'s meta data, **commit**'s data, and the **difference**.

**Example**
```git
$ git show v4.0
```

**result**
```git
tag v4
Tagger: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Wed Jun 15 09:48:20 2022 +0300

this is a tag version 4.0

commit 183400352c2b06bb6080839864a1de49d199794f (tag: v4, tag: v3)
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 18:50:09 2022 +0300

    add files

diff --git a/file.txt b/file.txt
new file mode 100644
index 0000000..e69de29
diff --git a/js/test.txt b/js/test.txt
new file mode 100644
index 0000000..e69de29
diff --git a/newFile.txt b/newFile.txt
deleted file mode 100644
index 3ba3b1e..0000000
--- a/newFile.txt
+++ /dev/null
@@ -1,5 +0,0 @@
-Fil a content
-
-Change locally
-
-Here is a change on remote repository
```