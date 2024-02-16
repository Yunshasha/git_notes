### Create .gitignore file

#### Step 1: create a '.gitignore' file

```
touch .gitignore
```

#### Step 2: edit '.gitignore' file

```
# Dependency directories
node_modules/

# Build output directory
build/

# Environment files
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# IDE and editor directories
.idea/
.vscode/
*.swp
*.swo

# OS generated files
.DS_Store
Thumbs.db

# Temporary files
npm-debug.log*
yarn-debug.log*
yarn-error.log*
```

#### Step 3: save and close

#### Step 4: add and commit it to you repo

```
git add .gitignore
git commit -m "Add .gitignore"
```

#### Step 5: push changes to remote repo

```
git push
```
