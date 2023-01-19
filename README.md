# 2023-01-17: DSCI 310 Git Demo
Intro Git Demo

- `git clone <URL>`: takes what's on github and does a one time download to your computer
- `git add <FILE>`: add the <FILE> to the staging area
- `git commit`: create the commit (aka snapshot)
  - `git commit -m "MESSAGE"`: create the git message directly in the command line
  
- `git push <WHERE> <WHAT>`: take local commits on `<WHAT>`, and send it to `<WHERE>`
  - e.g., `git push origin main`, sends codes from branc `main` local computer to the `remote` origin
- `git pull <WHERE> <WHAT>`: take remote commits on `<WHAT>`, and pull from `<WHERE>`
  - e.g., `git pull origin main`
- `git log --oneline --graph --all`: shows you all your history

## Branches
- `git branch <name>`: create a branch named wherever you are (`HEAD`)
- `git switch <name>`: go to that branch
  - `git checkout <name>`: go to that branch (older version)
- `git switch -c branch`: create a branch and move to it in 1 comment
  - `git checkout -b <name>`: same thing using `checkout`

### Cleanup Process
1. delete branch Pull Request in github
2. `git fetch --prune`: update references to deleted branches on the remote
3. `git branch -d <name>`: delete local branch `<name>`