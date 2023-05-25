### Merge branch into main
```
git fetch
git rebase origin/main
git checkout main
git merge <branch>
git push origin main

git checkout <branch>
    or
git branch -d <branch>
git push origin :<branch>
```

Does this work?
```
git fetch
git rebase origin/main
git checkout main
git merge <branch>
git branch -d <branch>
git push origin main:<deleted-branch>
```
