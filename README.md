# Bundle 1

Exerscise 1
```bash
git init
git branch -b master main
git add . 
git commit -m "adding changes"
git remote add origin https://github.com/13XAVI/Gym-Git-Exercise-Solutions.git
git push origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
```

Exercise2
```bash
git stash save "Saving home.html to remote"
git stash save "Saving about.html  to remote"
git stash save "Saving team.html to remote"
git stash list
git stash pop 'stash@{1}'
git stash apply 'stash@{1}'
git stash pop 'stash@{0}'
git reset --hard HEAD
```