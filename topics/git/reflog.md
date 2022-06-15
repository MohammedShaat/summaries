# Reflog

`git reflog`

Shows track **updates** of the branches's **tips/HEADs**. like (clone, commit, reset, checkout, pull)

**Example**
```git
$ git reflog
```

**result**
```git
7fd467f (HEAD -> update-branch, origin/update-branch) HEAD@{0}: commit: Add new files of git
2d69e53 (origin/main, origin/HEAD, main) HEAD@{1}: checkout: moving from main to update-branch
2d69e53 (origin/main, origin/HEAD, main) HEAD@{2}: pull: Fast-forward
2032b28 HEAD@{3}: checkout: moving from update-branch to main
f3f329c HEAD@{4}: commit: Add topics/git/images/, topics/git/compare-differences-between-two-commits.md, create-a-new-branch.md, get-help-for-log-command.md, switch-to-another-branch.md
d60d80c HEAD@{5}: commit: Edit topics/git/add-dot-add-a-add-u.md
fdac8d6 HEAD@{6}: commit: Add topic/git/add-dot-add-a-add-u
5ef060d HEAD@{7}: commit: Add new files of git commands
7f14600 HEAD@{8}: rebase (continue) (finish): returning to refs/heads/update-branch
7f14600 HEAD@{9}: rebase (continue) (pick): Add topics/git/get-help-for-log-command, and help-log.png
40ae149 HEAD@{10}: rebase (continue): Fix Conflict of rebase<message>
88fd005 HEAD@{11}: pull --rebase (start): checkout 88fd005a9665430c9eb6f39e63c814fb31f3487c
c5ec9e5 HEAD@{12}: reset: moving to HEAD
:
```