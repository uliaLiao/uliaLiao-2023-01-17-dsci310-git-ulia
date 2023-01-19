#2023-01-17: DSCI 310 Git Demo
Intro Git Demo

- `git clone <URL>`: takes what's on github and does a one time download to your computer
- `git add <FILE>`: add the <FILE> to the staging area
- `git commit`: create the commit (aka snapshot)
  - `git commit -m "MESSAGE"`: create the git message directly in the command line
  
- `git push <WHERE> <WHAT>`: take local commits on `<WHAT>`, and send it to `<WHERE>`
  - e.g., `git push origin main`, sends codes from branc `main` local computer to the `remote` origin
- `git pull <WHERE> <WHAT>`: take remote commits on `<WHAT>`, and pull from `<WHERE>`
  - e.g., `git pull origin main`
