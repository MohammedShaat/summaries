# Delete A Remote Branch Locally

**Two Steps**
1. Delete the local branch: `git branch -d <branch name>`
2. Delete the remote branch: `git push <remote name> --delete <branch name>`

\
**Example**
**Step 1**
```git
$ git branch -d update-branch
```

**result**
```git
Deleted branch update-branch (was 16f266a).
```

---

**Step 2**
```git
$ git push origin --delete update-branch
```

**result**
```git
To github.com:MohammedShaat/Summaries.git
 - [deleted]         update-branch
```