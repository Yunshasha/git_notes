### check branch now

```
git branch
```

### change you default branch to <main>

```
git config --global init.defaultBranch main
```

### create a new branch

```
git branch <branch-name>
```

### switch to another branch

```
git checkout <branch-name>

#########create and switch at meantime
git checkout -b <branch-name>
```

### merge the branch

```
########## switch to the main branch
git checkout main

########## merge current branch to <main>
git merge <current-branch>
```
