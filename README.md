## At first
```
git config --global user.name "[user.name]"
git config --global user.email "[user.email]"
```

## At non existing repository
```
git init:[Optional]
git add -A
git commit -m "[message]"
git push
--------------------------------------------
echo "# test_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/so-lovely/test_repo.git
git push -u origin main
```

## At existing repository
```
git remote add origin [address]
git branch -M main
git push -u origin main
```

## Make sure you should have dir or file
```
LICENSE
README.md
experiment[dir]
experiment.ipynb
.gitignore
src[dir]
pyproject.toml
requirements.txt
Outline[dir]
```

## Make sure you should exec
```
virtualenv [folder_name]
source bin/activate
```

### git clone makes new directory


