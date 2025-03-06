# git-learning

## Git

```sh
mkdir learn1
cd learn1
git init
vi README.md
git status
git add README.md
git status
git commit -m 'Initial commit'
```

## Git Branching
```sh
git checkout -b develop
vi myfirstscript.sh
git status
git add myfirstscript.sh
git commit -m "Initial commit in develop"
```

## Git Merge
```sh
git checkout master
git merge develop
ls -ltr
```
