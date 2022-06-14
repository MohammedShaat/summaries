# List Commits

`git log`

It lists commits with details: authors's info (name and email), commit's info (SHA and message), and date. 

**Example**
```
$ git log
```

**result**
```
commit 2032b28b5ca0fafbb147477e9655840fa59fb8f0 (HEAD -> main, origin/main, origin/HEAD)
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 12:49:18 2022 +0300

    Add git files

commit 0e2dbdbb0780ef3de6a1fface5762aaaa7effe8c
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 12:09:08 2022 +0300

    Edit readme.md, Add Git lists of links

commit afd48b9b28b243fa43806627a080acba437a7d48
Merge: c551cf9 f388f55
Author: Mohammed Osama Shaat <62177897+MohammedShaat@users.noreply.github.com>
Date:   Tue Jun 14 10:03:34 2022 +0300

    Merge pull request #5 from MohammedShaat/update-branch

    Split searchingTechniques.md to sub files
```

## List Each Commit in Only One line

`git log --oneline`

Lists commits every commit in oneline, with commit's hash and message.

**Example**
```
$ git log --oneline
```

**result**
```
2032b28 (HEAD -> main, origin/main, origin/HEAD) Add git files
0e2dbdb Edit readme.md, Add Git lists of links
afd48b9 Merge pull request #5 from MohammedShaat/update-branch
```

## Show A Graphical Overview Of Branching And Merging

`git log --graph`

**Example**
```
$ git log --oneline --graph
```

**result**
```
* 2032b28 (HEAD -> main, origin/main, origin/HEAD) Add git files
* 0e2dbdb Edit readme.md, Add Git lists of links
*   afd48b9 Merge pull request #5 from MohammedShaat/update-branch
|\
| * f388f55 Edit readme.md, edit the note
| * 08c2283 Modify folder icon's link
| * ba54ff4 Move topics/searchingTechniques.md to trash/.  And change the link icon
| * 9a22adb Modify 'readme.md'. Markdown's link and Searching Techniques's link to theri readme.md -2
| * 38df451 Add topics/markdown/readme.md and topics/searching-techniques/readme.md
| * 1586891 Modify topics/markdown/readme.md
| * a0177c1 Add topics/markdown/readme.md
| * 082c62f Modify readme.md, create links to sub searchin-techniques files
| * dea9c7d Add topics/searching-techniques/after.md, and-or-plus.md, asterisk.md, before.md, double-dot.md, file.md, hyphen.md, intitle.md, link.md, or.md, quotation.md, related.md, site.md, tilde.md files
| * f062403 Move topics/markdownSyntax.md to trash
| * f0eabea Modify readme.md, Markdown's link
|/
*   c551cf9 Merge pull request #3 from MohammedShaat/update-branch
```

## List Commits Of All Branches

`git log --all`

When there is a branch ahead of the current branch by N commits those aren't listed. So `--all` lists commits including ahead branches' commits. 

**Example**

**Wihtout** using `--all`
```
$ git log --oneline --graph
```
**result**
```
* 2032b28 (HEAD -> main, origin/main, origin/HEAD) Add git files
* 0e2dbdb Edit readme.md, Add Git lists of links
*   afd48b9 Merge pull request #5 from MohammedShaat/update-branch
```

---

**With** using `--all`
```
$ git log --oneline --graph -all
```

**result**
```
* 471def9 (update-branch) Edit topics/git/list-commits.md
* f885ecc (origin/update-branch) Add topics/git/list-commits.md
* 2032b28 (HEAD -> main, origin/main, origin/HEAD) Add git files
* 0e2dbdb Edit readme.md, Add Git lists of links
*   afd48b9 Merge pull request #5 from MohammedShaat/update-branch
```