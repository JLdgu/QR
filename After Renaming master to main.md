# After Renaming master to main

First rename master to main on Github

Then locally
```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```