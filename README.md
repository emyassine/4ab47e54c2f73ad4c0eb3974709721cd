# A HOW TO
```bash
rm -rf .git
git init
git add .
git commit -m "WIP"
git remote add origin https://github.com/[AUTHOR]/[REPO].git

git fetch origin main

git rebase -X theirs origin/main

git push -u origin main
```
