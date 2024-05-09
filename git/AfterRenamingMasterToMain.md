First rename master to main on Github

Then locally
```powershell
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
