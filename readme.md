# Git Guide
### 1. Config user
```
git config --global user.name "Zharith Salguero" #config para editar
git config --global user.email "458616.clot@fje.edu"
git config --list
```
### 2. Git init
```
mkdir "Repository Name" #crear un archivo
cd ".\Repository Name"  #cd es para el cambio de libreria
git init 
dir -hidden #dir es para desglosar un archivo

```
### 3. First commit
```
git status 
git add .\readme.md #agregar contenido a un archivo
git status
git commit -m "Commit message: brief description"
git status
```
### 4. Create branch
```
git branch dir/branch-name
git status
```
### 5. Create branch
```
git checkout dir/branch-name
git status
```
### 6. Merge to master
```
get checkout master
git status
git merge dir/branch-name
git status
git log
```
### 7. Create Stah
```
git status
git stash
git status
```
### 8. Apply Stash
```
git stash list
git stash apply
git status
```
### 9. Drop Stash
```
git stash list
git stash drop 1
git stash list
```
### 10. Pop Stash
```
git stash list
git stash pop
git stash list
```
### 11. Revent commit
```
git log --online
git revert [COMMIT_ID]
```
### 12. Cherry Pick
```
git log --online
git cherry-pick [COMMIT_ID]
```