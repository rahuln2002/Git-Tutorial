# Git Tutorial

### Git Configuration
```bash
git config --global user.name "<first-name last-name>"
git config --global user.email "<email>"
```

### Git Commands
1. initialize local repository
```bash
git init
```
2. check files status
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
git remote add origin <link.git>
```
8. check from where `fetch` and `push` is done: origin(`local`)
```bash
git remote -v
```
9. push file(s) from origin(`local`) to `main`
```bash
git push origin Main
```
10. restore any changes done in `local`
```bash
git restore
```