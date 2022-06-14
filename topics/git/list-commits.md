# List Commits

`git log`

It lists commits with details: authors's info (name and email), commit's info (SHA and message), and date. 

**Example**
```
$ git log
```

**result**
```
commit f885ecc0bdb6488ce901868262a4c13f600fea9b (HEAD -> update-branch, origin/update-branch)
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 13:49:15 2022 +0300

    Add topics/git/list-commits.md

commit 2032b28b5ca0fafbb147477e9655840fa59fb8f0 (origin/main, origin/HEAD, main)
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 12:49:18 2022 +0300

    Add git files

commit 0e2dbdbb0780ef3de6a1fface5762aaaa7effe8c
Author: Mohammed Shaat <mohammedshaat.it@gmail.com>
Date:   Tue Jun 14 12:09:08 2022 +0300

    Edit readme.md, Add Git lists of links

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
f885ecc (HEAD -> update-branch, origin/update-branch) Add topics/git/list-commits.md
2032b28 (origin/main, origin/HEAD, main) Add git files
0e2dbdb Edit readme.md, Add Git lists of links
```

## Show A Graphical Overview Of Branching And Merging

`git log --graph`

**Example**
```
$ git log --graph
```

**result**
```
* f885ecc (HEAD -> update-branch, origin/update-branch) Add topics/git/list-commits.md
* 2032b28 (origin/main, origin/HEAD, main) Add git files
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