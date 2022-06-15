# Synchronize/Push Changes To The Remote Repository

* **If it hasn't set up yet: `git push -u <remote name> <branch name>`. (It's used only in the first time)**

* **If it's already set up: `git push`**

**Example**
**1**
```git
$ git push -u origin update-branch
```

**result**
```git
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 1.03 KiB | 1.03 MiB/s, done.
Total 11 (delta 3), reused 1 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
remote:
remote: Create a pull request for 'update-branch' on GitHub by visiting:
remote:      https://github.com/MohammedShaat/Summaries/pull/new/update-branch
remote:
To github.com:MohammedShaat/Summaries.git
 * [new branch]      update-branch -> update-branch
branch 'update-branch' set up to track 'origin/update-branch'.

```