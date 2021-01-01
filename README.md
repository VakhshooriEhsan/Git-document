# Git-document


## Initialization
### init:
```shell
$ git init
```


## Staging
### add:
```shell
$ git add <file-name>
$ git add -A
```
### reset:
```shell
$ git reset <file-name>
```

## Commit
### commit:
```shell
$ git commit -m "<commit description>"
```
### log:
```shell
$ git log
```

## Tag:
### tag:
```shell
$ git tag
$ git tag -a <version> -m "<message>"
$ git tag -a <version> <commit-key> -m "<message>"
```

## Branch
### branch:
```shell
$ git branch
$ git branch <branch-name>
$ git branch -d <branch-name>
```

## Merge
### merge:
```shell
$ git merge <branch-name>
```

## Remote
### clone:
```bash
$ git clone <Git-address>
```
### push:
```bash
$ git push origin <branch-name>
```
### pull:
```bash
$ git pull origin <branch-name>
$ git pull origin <tag-version>
```
### remote:
```bash
$ git remote add origin <origin-address>
```


## Different
### diff:
```shell
$ git diff HEAD
$ git diff --staged
```

## Movement
### checkout:
```shell
$ git checkout -- <file-name>
$ git checkout <branch-name>
$ git checkout <tag-version>
```

## Show
### show:
```shell
$ git show <commit-key>
$ git show <tag-version>
```

## Blame
### blame:
```shell
$ git blame <file-name> -L<first-line>,<last-line>
```
