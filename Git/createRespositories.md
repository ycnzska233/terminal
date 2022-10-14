# Create Respositories

## Create a repository on the command line
```
$ echo "# repository" >> READ.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin SSH
$ git push -u origin main
```

## Push an existing repository from the command line
```
$ git remote add origin SSH
$ git branch -M main
$ git push -u origin main
```