# Git Tutorial

### Git Configuration
Set name and email address associated with version maker
```bash
git config --global user.name "<first-name last-name>"
git config --global user.email "<email>"
```

### Git Commands
0. clone a repository
```bash
git clone <repository-link.git>
```
1. initialize local repository
```bash
git init
```
2. check files status (file(s) modified or staged)
```bash
git status
```
3. add file(s) to be commited and pushed
```bash
git add <file-name>
  # or
git add .
```
4. commit file(s) to staging environment
```bash
git commit -m "<comment>"
```
5. check current branch
```bash
git branch
```
6. branch rename
```bash
git branch -m Main
```
7. connect origin(`local`) repository to `main` repository
```bash
git remote add origin <repository-link.git>
```
8. check from where `fetch` and `push` is done: origin(`local`)
```bash
git remote -v
```
9. push file(s) from origin(`local`) to `main`
```bash
git push origin Main
```
10. restore any changes done in `local` back from `main`
```bash
git restore
```
11. unstage file(s)
```bash
git restore --staged <file-name>
  # or
git reset
```
12. changes in file(s) but not staged
```bash
git diff
```
13. changes in file(s) staged but not commited
```bash
git diff --staged
```
14. create new branch
```bash
git branch <new-branch-name>
```
15. switch to another branch
```bash
git checkout <branch-name>
```
16. merge a branch to current branch
```bash
git merge <branch-name>
```
17. history of commits in current branch
```bash
git log
```
18. fetch and pull commits from tracking remote branch (resolving conflicts)
```bash
git pull
```