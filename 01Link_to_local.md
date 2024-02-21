## The basic proceduce <br> --- _How to link your project_

<br />

### 1st You alreay have local project

_you have a project in local and you want to upload all into your cloud_
<br/>

#### a), cd to your project path

```
cd path/to/your/project
```

#### b), Initialize a git repo

```
git init
```

#### c), Add the files you want to update

```
git add . // in this case, add all
```

#### d), Commit the files

```
git commit -m "Initial commit"
```

#### e), Add a remote repo

```
git remote add origin <repository_URL>
```

_if you dont have origin_

```
git remote -v // check if you have orgin

# To add a new remote named "origin"
git remote add origin <remote_repository_url>

# To update the URL of an existing remote named "origin"
git remote set-url origin <new_remote_repository_url>
```

#### f), Push to your remote cloud

```
// the full command: git push -u orgin <local-repo-branch>:<remote-repo-branch>, when this two branches have the same name, omit one
git push -u origin main

### sometimes you can't push, try, -f cover the remote with current code
git push -f origin main

### when push, create a link remote(origin) to tell the repo, my local master branch want to connet remote main branch
git push --set-upstream origin master : main
```

<br />

### 2nd You haven't create project yet

_In this case, you don't have you project yet, but you want to link to remote repo and upload new commit after every edit_

#### a), Use clone repo to have a project in local

```
git clone <remote_repo_URL>
```

#### b), Add the files you want to update

```
git add . // in this case, add all
```

#### c), Commit the files

```
git commit -m "Initial commit"
```

#### d), Push to your remote clould

```
git push
```
