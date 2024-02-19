## The basic proceduce How to link your project

### 1st You alreay have local project

_you have a project in local and you want to upload all into your cloud_
<br/>

#### a),cd to your project path

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

**if you dont have origin**

```
git remote -v // check if you have orgin

# To add a new remote named "origin"
git remote add origin <remote_repository_url>

# To update the URL of an existing remote named "origin"
git remote set-url origin <new_remote_repository_url>
```

#### f), Push to your remote cloud

```
git push -u origin main

# sometimes you can't push, try
git push -f orgin main
```

### 2nd, You haven't create project yet

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
