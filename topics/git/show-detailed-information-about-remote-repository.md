# Show Detailed Information About Remote Repository

`git remote show <remote name>`

**Exmaple**
```git
$ git remote show origin 
```

**result**
```git
* remote origin
  Fetch URL: git@github.com:MohammedShaat/Summaries.git
  Push  URL: git@github.com:MohammedShaat/Summaries.git
  HEAD branch: main
  Remote branches:
    main          tracked
    update-branch tracked
  Local branches configured for 'git pull':
    main          merges with remote main
    update-branch merges with remote update-branch
  Local refs configured for 'git push':
    main          pushes to main          (up to date)
    update-branch pushes to update-branch (up to date)

```