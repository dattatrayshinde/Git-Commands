## Git-Commands
Git Commands


#### To set account

```javascript
 git config --global user.name "{User name}"
 git config --global user.email "{Email}"
```

#### Cloning project from GttHub

```javascript
 git clone {git url}
```

#### Existing project Folder if we have to push to GitHub

```javascript
 cd existing-project
 git init
 git add --all
 git commit -m "Initial Commit"
 git remote add origin {git url}
 git push -u origin master
```
You will authentication dialogue while pushing code 

#### If you already have GitHub Project on machine then set this folder to "origin" to push to.

```javascript
 cd existing-project
 git remote set-url origin {git url}
 git push -u origin master
```

#### Done.. This is sufficient to start with Git... !
