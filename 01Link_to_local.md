## The basic proceduce How to link your project

### 1st You alreay have local project

**you have a project in local and you want to upload all into your cloud**
<br/>

#### First,cd to your project path

```
cd path/to/your/project
```

#### Second, Initialize a git repo

```
git init
```

#### Third, Add the files you want to update

```
git add . // in this case, add all
```

#### Fourth, Commit the files

```
git commit -m "Initial commit"
```

#### Fifth, Add a remote repo

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

#### Final, Push to your remote cloud

```
git push -u origin main
# sometimes you can't push, try
git push -f orgin main
```
